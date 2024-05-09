I've put these points in a separate section because, in my opinion, it currently represents one of the most comprehensive and understandable guides for intelligently hiding modifications in the system from applications on Android. I'm particularly interested in all updates regarding this aspect, actively tracking and testing all methods on my own working device.

## Obtaining Root Access
The author recommends using the first option due to its convenience, functionality, and stability.

### Kitsune Mask (recommended)
<sup>*fork of Magisk, previously Magisk Delta*</sup>

1. Use [Kitsune Mask (app-release.apk).](https://github.com/HuskyDG/magisk-files/releases)
2. In the Kitsune Mask settings, rebuild the application with a random package name, enable Zygisk and MagiskHide (you can also optionally enable biometric authentication for your convenience).
3. Configure hiding:
   * Set up Hide. In the list, select the applications from which you want to hide root access.
   * Use SuList. Enable the corresponding setting, then reboot. Afterwards, select the applications from the list that will have access to root permissions and be able to request them.  
**Recommendation for using SuList: activate the option _only after_ installing (and configuring, if necessary) all necessary modules.** Otherwise, installing any module with its own application (for example, BCR or V4AFX) will lead to a bootloop. If you need to make any changes to the modules (installation/removal, update, change of status), **_TURN OFF SuList_**, reboot your device, and only then make changes. Then you can turn SuList back on.

### KernelSU
1. Install [KernelSU](https://kernelsu.org/) and its manager [using any available method for you.](https://kernelsu.org/guide/installation.html)
2. In the KSU Manager, install the [Zygisk Next module,](https://github.com/Dr-TSNG/ZygiskNext/releases) reboot, and in the module settings menu (press "Open"), enable the "Enforce Denylist" option. Reboot your device.
3. Go to the Superuser tab and select the applications that should have access to root permissions.

P.S. Here's the first downside of KernelSU – you simply cannot hide the root manager application, as you can with repackaging the package in Magisk. Therefore, you have two working options here: hide the KernelSU manager application [using Hide My Applist](#hide-my-applist-for-lsposed) or remove it from the system, accessing the manager's functionality through the CLI `ksud` as needed. Leaving the application in the system without hiding it is not recommended – all (even Russian) banking applications recognize it in the system and block their functionality.  
**There are absolutely no advantages to KSU over Kitsune Mask.** So, if your device is not officially supported – don't even bother with this nonsense, it's not worth your time and nerves. And in any case, I advise you to prefer the familiar and stable Magisk.

## Advanced Hiding of Custom Firmware, Modules, and Unlocked Bootloader

<details>

<summary>Why is all this necessary?</summary>

For the correct, one hundred percent concealment of any system interventions from the most fastidious applications.  
And here's the explanation. There are indeed very few "fastidious" ones. So far. Currently, the vast majority of applications are satisfied with hidden root permissions in Magisk Hide to perceive the device as safe and not restrict functionality (or not launch at all, like some games).  
However, hiding by Hide is not the end of the story, and other traces of various system interventions and the virginity of the device are still visible to all applications, and as soon as their developers introduce enhanced security checks, "everything will fall apart" – just update. Therefore, here we will tell you how to take care in advance to make our modifications impossible to detect and rid ourselves of potential surprises in the future. In simpler terms, all this is *for personal peace of mind,* but it may come in handy in the very near future.

</details>

Recommendations:  
1. ONLY stock firmware OR crDroid / EvolutionX, where developers have implemented spoofing of important values from build.prop, read by applications for the security level of the build, directly in the firmware "out of the box."  
For crappy firmware where this is not provided, there is the [Sensitive Props module,](https://github.com/begoniacommunity/list/tree/magisk-modules#sensitive-props) which, where possible, replaces important values in certain lines (without modifying read-only lines to avoid Property Modified detection). Nevertheless, some lineage-specific props may still be readable to all applications (this can be checked in any non-root shell by executing the command `getprop | grep 'lineage'` / or `'crdroid'`). This problem is currently solved only in EvolutionX; these props do not exist in vendor stock firmware, so they are our priority. You can also try to manually remove them if the filesystem on your device allows it.

### Instructions
0. Start with a "clean" system without any modules installed, and configure Kitsune Mask. You will need the following applications: [Native Detector,](https://t.me/reveny1) [Native Test,](https://t.me/LSPosed/256) [Momo](https://github.com/apkunpacker/MagiskDetection/blob/main/Momo-v4.4.1.apk), and [Memory Detector.](https://github.com/rushiranpise/detection/blob/main/MemoryDetector_2.1.0.apk) Hide root permissions in Magisk Hide for all four applications.
Install the previously mentioned [Magisk OverlayFS module.](https://github.com/HuskyDG/magic_overlayfs) Reboot your device.
   - It is strongly recommended to follow the [instructions above](https://github.com/begoniacommunity/list/blob/main/list/android.md#kitsune-mask) using Kitsune Mask.
   - OverlayFS does not work on the official Magisk version (27.0)!
   - [Using the module with KernelSU.](https://github.com/HuskyDG/magic_overlayfs#kernelsu-problem)
1. After installing the module, execute the command `su -mm -c magic_remount_rw` in Terminal (Shell).
2. **If you are on a custom firmware,** navigate to a file manager with root support (recommended [Material Files](https://github.com/zhanghai/MaterialFiles)), go to the /system/addon.d folder, and delete the file(s) from this folder. Change the permissions for the folder to 0000 (remove all checkboxes for all users). Visually, changes in permissions may not apply in the file manager, but they do work.
   - If you have an ext4 filesystem: navigate to the build.prop file in text editor mode and delete all lines containing `lineage`, `aosp`, or `crdroid`. Save the changes. If the changes are saved successfully, set permissions to 0600 for the build.prop file. If you receive an error `I/O error`, editing build.prop is not available to you.
   - Additionally, if necessary, make changes to the filesystem as desired.
3. Once everything is done, execute `su -mm -c magic_remount_ro` in Terminal.
4. Navigate to /data/adb/modules/magisk_overlayfs and open the file *mode.sh* with a text editor. Find the line `export OVERLAY_MODE=` and change the value from `0` to `2`.
5. Reboot your device and check if the changes have been applied. If not, repeat the previous step, as this sometimes happens.

Open Native Detector – among the detection outputs, there should only be the Native Test application (yes, it's that dumb). In the Native Test application, the output should be Normal.  
Open Momo – the local output should be limited to a maximum of two detections: "Device running a custom ROM" and/or "Bootloader unlocked". The first one is the result of the inability to hide lineage/aosp-specific strings, [the second one does not need an explanation](#block-the-bootloader---hide-the-unlocked). If there's anything about debugging mode, it's USB debugging, so ignore it.  
In Memory Detector, the output should be *Looks fine! Nothing is found.*

### Patching Modules
>
> [!IMPORTANT]
> This method may not work with hardcoded modules like Systemless BiTGApps. For modules that do not add/change anything in the system and system files respectively (e.g., Play Integrity Fix or Zygisk Detach), this procedure is not required.

[A list of modules for Magisk can be found here.](https://github.com/begoniacommunity/list/blob/main/list/android.md#%D0%BC%D0%BE%D0%B4%D1%83%D0%BB%D0%B8-%D0%B4%D0%BB%D1%8F-magisk)

1. Open the module archive and navigate to /META-INF/com/google/android. Open the update-binary file with a text editor.
2. Before the end of the module installation (usually the last line, typically `exit`), add the following script:
```
OVERLAY_IMAGE_EXTRA=0     # number of kb need to be added to overlay.img
OVERLAY_IMAGE_SHRINK=true # shrink overlay.img or not?

# Only use OverlayFS if Magisk_OverlayFS is installed
if [ -f "/data/adb/modules/magisk_overlayfs/util_functions.sh" ] && \
    /data/adb/modules/magisk_overlayfs/overlayfs_system --test; then
  ui_print "- Add support for overlayfs"
  . /data/adb/modules/magisk_overlayfs/util_functions.sh
  support_overlayfs && rm -rf "$MODPATH"/system
fi
```
If you encounter issues with adding the script (e.g., the installation completion line in update-binary is missing altogether), add it to customize.sh or install.sh.

3. Save the edited file and move it back to the installation archive, replacing the original file.
4. Install the module. If everything is successful (you correctly inserted the script, and the module supports installation via OverlayFS), the installation log will display a similar output to when installing the OverlayFS module itself.
5. Reboot your device and check:
   - the module itself to ensure everything is working correctly;
   - the detection of files in Memory Detector – the output should be *Looks fine! Nothing is found.*
   
## [LSPosed Mod](https://drive.google.com/file/d/1-vxugvuG1J5ZMySv7MVbr6QrvNhfERFa/view?usp=drivesdk)
<sup>*(download link in the header)*</sup>

>
> [!NOTE]
> 🎉 The issue with detecting LSPosed and its application injections has been partially resolved. The link above contains a build with logging disabled (yes, this was the actual reason for the notorious "evil service" triggering in detectors). Now you can safely use modules that inject into the system framework, system interface, and other "system" components, as well as into applications without root access checks (or without restricting functionality in such cases respectively). These modules and injections, as well as the presence of active LSPosed in the system, cannot be detected by other applications, including various "root checkers".
> ___
> ℹ️ There may still be issues with injecting individual modules into the rarest set of applications with the ultimate level of checks. Typically, such use cases are almost non-existent or simply do not make sense. Most likely, this won't affect you at all. It's important to note that, for example, modules like Hide My Applist or Disable FLAG_SECURE do not require integration into any specific application (as they work with all applications in the system) – they are injected through the framework and therefore remain undetectable.

The development of the original LSPosed has recently been abandoned by its author. After a few months, an enthusiast stepped up to further develop his own fork. Now you can install it even on Android 14 QPR2.

[A list of modules for LSPosed can be found here.](https://github.com/begoniacommunity/list/blob/main/list/android.md#%D0%BC%D0%BE%D0%B4%D1%83%D0%BB%D0%B8-%D0%B4%D0%BB%D1%8F-lsposed)

### [Hide My Applist for LSPosed](https://github.com/Dr-TSNG/Hide-My-Applist/releases)
<sup>*(download link in the header)*</sup>

1. Download and install Hide My Applist, then reboot your device.
2. Go to LSPosed → Modules → enable Hide My Applist (a checkmark will automatically be placed on System framework). Reboot your device.
3. Open Hide My Applist, make sure the module is activated, and the system service is working. Go to Template Management → Create a template with a blacklist → select everything you want to hide. Add a name for the template and save it.
4. Go back to the main menu and open App Management. Find the applications you want to hide something from. In the menu of each of them, enable hiding and apply the template you created earlier (the first item in the "Template Configuration" section).

## Carefully Inject ReVanced into Original YouTube
> [!WARNING]
> Frankly, using the root version of YouTube with ReVanced is currently a very controversial solution.
> Yes, indeed, the traces of module mounting will disappear, but using this combination is very problematic: firstly, the cold start of the application becomes 2-3 times longer than usual; secondly, when switching to the YouTube app through a link, the normal, unmodified app launches (i.e., without injection). It's up to you to decide.

>
> [!TIP]
> If you want perfect and painless hiding, there is always an alternative in the form of the [non-root version of ReVanced Extended.](https://github.com/MatadorProBr/revanced-extended-magisk-module/releases)

1. Download and install the [Zygisk Proc Injection module,](https://github.com/HuskyDG/magic_proc_monitor) then reboot your device.
2. Now download and install the [version of the original YouTube](https://www.apkmirror.com/apk/google-inc/youtube/) that is already used as the base for the [ReVanced Extended build.](https://github.com/MatadorProBr/revanced-extended-magisk-module/releases) Download the corresponding root version.
3. Download the [YT Revanced Inject module:](https://t.me/pixelifysupport/124919)
   1) Open the module archive and edit the `module.prop` file: change `version=` from `18.45.43` to the version of YouTube client you selected (for example, `19.07.43`).
   2) Open the previously downloaded archive of the root version of ReVanced Extended and extract base.apk from it → rename it to revanced.apk and move it with replacement to the YT Revanced Inject module archive.
4. Save all changes and install the module.

## Block the Bootloader / Hide Unlocked
On Google Pixel and OnePlus devices, you can lock the bootloader with unofficial firmware installed (even with root permissions). This is possible on other devices that support custom AVB signatures (avb_custom_key) – using the [avbroot program.](https://github.com/chenxiaolong/avbroot/blob/master/README.ru.md) Such self-signed locking will not help pass the Strong certification in Play Integrity, but for the rarest set of applications checking the bootloader status and trust level, it will be sufficient.
For other devices, there is a less reliable (or rather partially working) method with the [BootloaderSpoofer module](https://github.com/chiteroman/BootloaderSpoofer) under LSPosed. Activate it for applications detecting an unlocked bootloader. There is a chance that this will help (for example, it helps with the Momo root checker and some games).