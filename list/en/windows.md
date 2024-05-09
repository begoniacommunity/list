# 🪟 Windows:

> [!NOTE]
> [Permanent activation of Windows 10-11 with hardware binding to the server:](https://github.com/massgravel/Microsoft-Activation-Scripts)  
Open PowerShell, run the command `irm massgrave.dev/get | iex`, choose **[1] HWID.** Done.

### ⚙️ System Configuration and Additions
* [SophiApp.](https://github.com/Sophia-Community/SophiApp) Fine-tuning of the working environment. Uses only what is achievable through documented Windows functionality by developers.<sup>[`ℹ️`](https://github.com/Sophia-Community/SophiApp?tab=readme-ov-file#key-features)</sup>
* [VCRHyb64.](https://t.me/begoniacommunity/1310689) Collection of all installed Visual C++ Redistributable 2005-2022 versions, installs both x86/x64 versions.
* [.NET Runtime](https://dotnet.microsoft.com/en-us/download/dotnet-framework)<sup>[`ℹ️`](https://github.com/begoniacommunity/list/blob/main/list/info.md#net-runtime)</sup> and [VCLibs.](https://learn.microsoft.com/ru-ru/troubleshoot/developer/visualstudio/cpp/libraries/c-runtime-packages-desktop-bridge#how-to-install-and-update-desktop-framework-packages)<sup>[`ℹ️`](https://github.com/begoniacommunity/list/blob/main/list/info.md#vclibs)</sup> Sometimes necessary dependencies.
* [SKTimeStamp.](https://tools.stefankueng.com/SKTimeStamp.html) Adds a section for precise modification of creation/modification/access time through file properties in File Explorer.
* [Windows Terminal.](https://github.com/microsoft/terminal/) Microsoft's terminal with extensive customization, supports any kind of console, be it cmd, PowerShell, or WSL. Immediately set it as the default command-line application.<sup>[`ℹ️`](https://learn.microsoft.com/ru-ru/windows/terminal/install#set-your-default-terminal-application)</sup>
* [SuperF4.](https://github.com/stefansundin/superf4/releases/download/v1.4/SuperF4-1.4.exe) "Forcibly closes" a hung window, in other words, kills its process, using the Ctrl+Alt+F4 key combination. Used by you instead of the standard Alt+F4 combination, which doesn't help in cases of a hung process.
* [Monitorian.](https://apps.microsoft.com/store/detail/monitorian/9NW33J738BL0) Adjusts the brightness of external monitors<sup>[`ℹ️`](https://github.com/emoacht/Monitorian#detection-of-external-monitors)</sup> through Windows.
* [Process Hacker 2.](https://processhacker.sourceforge.io/downloads.php) Manages running processes in the system. An advanced alternative to Task Manager and Resource Monitor.<sup>[`ℹ️`](https://processhacker.sourceforge.io/)</sup> Installation in full mode is strictly recommended.

### 🎨 Personalization
* [BeautySearch.](https://github.com/krlvm/BeautySearch) Modifications for the built-in search in the taskbar.
* <sup>`(Windows 10)`</sup>[TrayVolumeControl.](https://github.com/krlvm/TrayVolumeControl) Adjusts the volume with the mouse wheel when hovering over the volume icon. You quickly get used to it, and it becomes inconvenient without it, I recommend it.
* <sup>`(Windows 10/11 <22H2)`</sup>[EarTrumpet.](https://eartrumpet.app/) An alternative sound control menu for the taskbar. The main benefit is having an application volume mixer under the common volume slider. Switching the sound source by right-clicking the icon.<sup>[preview](https://github.com/begoniacommunity/list/blob/main/list/info.md#eartrumpet)</sup> Also, it has volume adjustment by wheel by default when hovering over the icon, so the above program is not needed.
* <sup>`(Windows 11)`</sup>[MicaForEveryone.](https://github.com/MicaForEveryone/MicaForEveryone) Customization of the appearance of Win32 application windows.
* <sup>`(Windows 11)`</sup>[StartAllBack.](https://t.me/repack_me_clone) Essential software for a comfortable transition from Windows 10 to 11. You can use the "Proper 11" preset or configure everything manually. Normal taskbar, improved dark mode, and accent color for Win32 elements, acrylic background for the classic context menu, volume adjustment with the mouse wheel, and more. Give it a try.
* <sup>`(Windows 10/11)`</sup>[ExplorerBlurMica.](https://github.com/Maplespe/ExplorerBlurMica) Software for adjusting the acrylic effect (as in Windows 10) or Mica for File Explorer windows.

<details>

<summary>Recommended settings for Windows 11</summary>

1. For [MicaForEveryone:](https://github.com/MicaForEveryone/MicaForEveryone) set everything to "Default" in the "Global Rule" section, creating a separate config for each program in the future. Choose the window title color according to the program theme; background to Tabbed; enable "Extend window frame into client area".
2. [StartAllBack:](https://www.startallback.com/) open the "Run" window (Win+R), run the command `startisbackcfg /magic`. The StartAllBack properties window will open in the Magic section, enable the Cast dark magic option.
3. [ExplorerBlurMica:](https://github.com/Maplespe/ExplorerBlurMica) configure the Mica effect for all File Explorer windows in Windows 11:
   * **All three** programs must be installed: Mica For Everyone, StartAllBack, and ExplorerBlurMica.
   * Cast dark magic option must be activated in StartAllBack.
   1. Go to the config.ini file located in the ExplorerBlurMica folder.
   2. Edit the content of the lines:  
   Change `effect` to `2`  
   Change `clearWinUIBg` to `false`<sup>[preview](https://github.com/begoniacommunity/list/blob/main/list/info.md#explorerblurmica-false)</sup> or leave it as `true`<sup>[preview](https://github.com/begoniacommunity/list/blob/main/list/info.md#explorerblurmica-true)</sup> – try which option you prefer.  
   In the `[dark]` tree, change `a` to `255`. Everything else (r, g, b) should be set to `0`.  
   3. Open Mica For Everyone and completely delete the explorer preset.
   4. Add rules for the `#32700` and `OperationStatusWindow` classes. Set Background to *Tabbed* and enable Extend frame into client area for both.
   5. Forcefully restart File Explorer.
</details>

* [Windhawk.](https://github.com/ramensoftware/windhawk) Implementation of injections and hooking in Windows.
  * [Windows 11 Start Menu Styling.](https://github.com/ramensoftware/windows-11-start-menu-styling-guide) [Various styles](https://github.com/ramensoftware/windows-11-start-menu-styling-guide#themes) for the Start menu in Windows 11. For example, hiding the "Recommendations" section or adding layout with pinned apps and a list of all apps. [Instruction.](https://github.com/ramensoftware/windows-11-start-menu-styling-guide#introduction)
* [MSEdgeRedirect.](https://github.com/rcmaehl/MSEdgeRedirect) Customization for news panels, weather, and changing the default browser for redirecting from system search.
* [Cursor Colors Synchronizer.](https://github.com/SunsetTechuila/Cursor-Colors-Synchronizer) Synchronizes the system accent color with a [custom cursor of choice.](https://github.com/SunsetTechuila/Cursor-Colors-Synchronizer#description)
* [WinPaletter.](https://github.com/Abdelrhman-AK/WinPaletter) Flexible customization of the color palette of various Windows interface elements.<sup>[`ℹ️`](https://github.com/Abdelrhman-AK/WinPaletter#-winpaletter-advanced-windows-appearance-editor)</sup>

### ⏺ Screen Sharing and Screen Recorders
* [RustDesk (Windows).](https://rustdesk.com/) Free alternative to AnyDesk/TeamViewer. Self-hosting is possible, but it works great on free servers from Germany and Kiev.
* [ShareX.](https://getsharex.com/) The best screenshot/recorder for Windows. In short: a mega-customizable program with fully open-source code. Convenient, precise selection of recording/snapshot areas, a wide selection of tools for editing screenshots, ability to record the screen using NVENC, automatically convert recorded video to GIF, optionally upload screenshots to various image uploaders selectively in a couple of clicks. All control via hotkeys. An absolute must-have.
* [OBS.](https://obsproject.com/ru) Advanced screen capture and streaming. Supports different scenes, convenient control panel, plugin support. Highly customizable.

### 🌸 Life
* [Lively Weather.](https://github.com/rocksdanister/weather) Gorgeous weather forecast app.

### 🤖 Emulation
* [(*EOL*)](https://github.com/microsoft/WSA/commit/5e0b982be3f6a9613d65a389d12554844d931bba) [WSABuilds.](https://github.com/MustardChef/WSABuilds) Windows Subsystem for Android, released with Windows 11. The repository contains builds for both Windows 11 and 10. There are variations with OpenGApps/MindTheGApps, Magisk/~~KernelSU~~. And the useless Amazon Store is cut out, of course. Installation is simple even for a hedgehog — unzip the archive and run Run.bat.

### 🖼 Media Content
* [Mp3tag.](https://mp3tag.de/en/download.html) Editing metadata in audio files.

### 🔈 Sound
* [Alternative A2DP Driver.](https://bluetoothgoodies.com/a2dp/) An essential tool for Bluetooth headphone owners with support for HiRes codecs like aptX HD and LDAC/LDHC. By default, Windows only supports AAC (Windows 11)/SBC codecs, significantly reducing the audio quality. This program is indeed a panacea, but... Attention: it's paid! There is a trial period during which the full functionality is available. Check compatibility with your headphones, then either the program stops working or you purchase a permanent hardware-bound license for $5.99. In rubles, at the time of writing, this is ~850 rubles, payable via a card [purchased on Plati.market.](https://plati.io/itm/1065234)
* [EqualizerAPO.](https://sourceforge.net/projects/equalizerapo/) The best equalizer for Windows, easy to install and doesn't harm the system. It offers a wide range of settings and the ability to save/apply presets for different parameters.

### 📄 Office
* [Notepad++.](https://notepad-plus-plus.org/downloads/) A text editor with wide community support. It supports plugins, themes, and various formats.
* [Office Tool Plus.](https://github.com/YerongAI/Office-Tool) Download, installation, flexible configuration, activation... basically, Office package management.
* [Okular.](https://okular.kde.org/en/) A universal reader from KDE for formats like PDF, EPub, Tiff, [and similar ones.](https://okular.kde.org/en/formats/)

### 🎞 Transcoding
* [HandBrake.](https://handbrake.fr/) Convert videos to almost any format based on various criteria.

### 🖥 Program Management
* [WingetUI.](https://github.com/marticliment/WingetUI) A graphical interface for managing the winget package manager. Among the most obvious conveniences, it automatically/selectively updates all installed software on your PC via winget. We recommend trying to start using this.
* [Uninstall Tool.](https://t.me/repack_me_clone) Advanced program uninstallation along with their "tails". Optionally, you can choose to install a service that will track installations and collect precise information about the installation of any software in the system.

### 📶 Network Management
* [Simplewall.](https://henrypp.org/product/simplewall) Traffic configuration using the Windows Filtering Platform (WFP).

### 📀 Writing Installation Images
* [Rufus.](https://rufus.ie) A straightforward tool for writing images.
* [Ventoy.](https://ventoy.net/en/index.html) Software for creating installation, multi/bootable flash drives. Extremely easy to use: just click to install the boot partition, then put the bootable .iso image(s) into the automatically created empty partition. Works with MBR and GPT (not always correctly).
* [Netboot.](https://netboot.xyz/) PXE bootloader<sup>[`ℹ️`](https://github.com/begoniacommunity/list/blob/main/list/info.md#pxe-%D0%B7%D0%B0%D0%B3%D1%80%D1%83%D0%B7%D1%87%D0%B8%D0%BA)</sup> for various installer/LiveCD systems. More complex than the above option.

### ⬇️ File and Download Management
* [7-Zip.](https://7-zip.org/) An archiver.
* [Free Download Manager.](https://freedownloadmanager.org/) A convenient download manager.
* [qBittorrent.](https://www.qbittorrent.org/) Torrent downloading.

### 💡 Useful
* [PowerToys.](https://github.com/microsoft/PowerToys) An application from Microsoft, like a collection of all-in-one utilities. It contains [a billion different useful things](https://github.com/microsoft/PowerToys#about), you will definitely find a use for it.
* [Sysinternals Suite.](https://docs.microsoft.com/en-us/sysinternals/downloads/sysinternals-suite) Another set of small utilities. You can download everything at once, or [what you need individually.](https://docs.microsoft.com/en-us/sysinternals/downloads/sysinternals-suite#introduction)

## ✈️ Telegram
* [64Gram.](https://github.com/TDesktop-x64/tdesktop) A simple modified client based on the official one [with a small number of useful additions.](https://github.com/TDesktop-x64/tdesktop/blob/dev/features.md)
* [Unigram.](https://github.com/UnigramDev/Unigram) A UWP client with Fluent design. Animations noticeably lag, but overall it's usable, although significantly less convenient than TGDesktop.

## 📟 Discord:
### Mods

* [Vencord + OpenAsar Bundle.](https://vencord.dev/) Wide support for useful plugins and themes from the community, speeding up the cold start of the program and improving overall performance in Discord.

Installation is done through the [Vencord installer.](https://github.com/Vencord/Installer/releases/latest/download/VencordInstaller.exe) Important: save it in any convenient place for you. Sometimes Vencord (and less often OpenAsar) are reset after updating Discord, in which case you need to restart the installer and reinstall them with the **Install Vencord** or **Reinstall / Repair** and **Install OpenAsar** buttons. This will restore the mods with all your settings, plugins, and themes.  
> [!NOTE]
> In the OpenAsar configuration, you can choose the performance mode. For desktop PCs/with constant power supply, it is recommended to use Performance, otherwise Balanced.

### Plugins  

<sup>*(all listed plugins are immediately available in the Vencord section → Plugins, you just need to activate them)*</sup>

* [AlwaysTrust.](https://vencord.dev/plugins/AlwaysTrust) Removes the popup about a suspicious site or file.
* [AnonymiseFileNames.](https://vencord.dev/plugins/AnonymiseFileNames) Anonymizes the names of sent files by assigning them random names.
* [BetterGifAltText.](https://vencord.dev/plugins/BetterGifAltText) Replaces the "GIF" tag with GIF tags or the file name.
* [BiggerStreamPreview.](https://vencord.dev/plugins/BiggerStreamPreview) Increases the preview size of streams.
* [NoScreensharePreview.](https://vencord.dev/plugins/NoScreensharePreview) Completely disables stream previews.
* [CallTimer.](https://vencord.dev/plugins/CallTimer) Adds a timer for call duration in voice chats.
* [ClearURLs.](https://vencord.dev/plugins/ClearURLs) Automatically removes trackers from links.
* [CopyUserURLs.](https://vencord.dev/plugins/CopyUserURLs) Adds a copy direct user URL option to the context menu.
* [CrashHandler.](https://vencord.dev/plugins/CrashHandler) *Attempts* to prevent application crashes.
* [DisableDMCallIdle.](https://vencord.dev/plugins/DisableDMCallIdle) Disables auto-kick from voice channels after three minutes of inactivity.
* [EmoteCloner.](https://vencord.dev/plugins/EmoteCloner) Quickly clones custom emojis/stickers to your server.
* [Experiments.](https://vencord.dev/plugins/Experiments) Provides access to experimental features.
* [FakeNitro.](https://vencord.dev/plugins/FakeNitro) Fakes some Nitro features (using fake emojis/stickers) and allows streaming in high quality.
* [FavoriteEmojiFirst.](https://vencord.dev/plugins/FavoriteEmojiFirst) When autocompleting, prioritizes your favorite emojis.
* [ForceOwnerCrown.](https://vencord.dev/plugins/ForceOwnerCrown) Forcibly displays a crown next to the server owner's name.
* [GifPaste.](https://vencord.dev/plugins/GifPaste) Instead of instantly sending a GIF, inserts a link to it in the input field.
* [GreetStickerPicker.](https://vencord.dev/plugins/GreetStickerPicker) Allows manual selection of a greeting sticker via right-click.
* [HideAttachments.](https://vencord.dev/plugins/HideAttachments) Adds a button to hide media and attachments on the input panel.
* [IgnoreActivities.](https://vencord.dev/plugins/IgnoreActivities) Settings for displaying selective activities.
* [iLoveSpam.](https://vencord.dev/plugins/iLoveSpam) Forcibly displays messages marked as potentially unwanted.
* [ImageZoom.](https://vencord.dev/plugins/ImageZoom) Zooms in on images and GIFs via Left-click + mouse wheel.
* [MessageLogger.](https://vencord.dev/plugins/MessageLogger) Temporarily saves deleted messages and edit history.
* [MoreUserTags.](https://vencord.dev/plugins/MoreUserTags) More tags for webhooks and moderation roles (staff, mod, etc.).
* [MuteNewGuild.](https://vencord.dev/plugins/MuteNewGuild) Mutes new servers you join.
* [MutualGroupDMs.](https://vencord.dev/plugins/MutualGroupDMs) Shows mutual groups in a user's profile.
* [NoBlockedMessages.](https://vencord.dev/plugins/NoBlockedMessages) Completely hides messages from users you've blocked.
* [NoF1.](https://vencord.dev/plugins/NoF1) Removes the help center call when pressing the F1 key.
* [NoProfileThemes.](https://vencord.dev/plugins/NoProfileThemes) Disables custom Nitro profile themes, bringing them to a uniform style.
* [NoUnblockToJump.](https://vencord.dev/plugins/NoUnblockToJump) Allows jumping to messages from users you've blocked.
* [OnePingPerDM.](https://vencord.dev/plugins/OnePingPerDM) Only one notification sound will play upon receiving multiple messages from a user in DMs.
* [OpenInApp.](https://vencord.dev/plugins/OpenInApp) Opens Spotify, Steam, and Epic Games links in their respective apps instead of the browser.
* [PermissionsViewer.](https://vencord.dev/plugins/PermissionsViewer) View permissions for users/channels/server roles.
* [PictureInPicture.](https://vencord.dev/plugins/PictureInPicture) Adds a Picture-in-Picture mode for videos (next to the download button).
* [PlatformIndicators.](https://vencord.dev/plugins/PlatformIndicators) Adds a platform indicator showing your online status (PC, phone, browser, etc.).
* [QuickMention.](https://vencord.dev/plugins/QuickMention) Adds a mention button to the input panel.
* [ReadAllNotificationsButton.](https://vencord.dev/plugins/ReadAllNotificationsButton) Displays a "Read all" button that clears all pending unread messages from all servers.
* [RelationshipNotifier.](https://vencord.dev/plugins/RelationshipNotifier) Notifies you if: you're removed as a friend; your friend request is declined; you're removed from a server or group.
* [RevealAllSpoilers.](https://vencord.dev/plugins/RevealAllSpoilers) Reveals all spoilers in a message by Ctrl+clicking on any of the spoilers/in the entire chat by Ctrl+Shift+clicking.
* [ReverseImageSearch.](https://vencord.dev/plugins/ReverseImageSearch) Adds a search by image option to the context menu of images.
* [RoleColorEverywhere.](https://vencord.dev/plugins/RoleColorEverywhere) Adds role colors everywhere except in the typing indicator.
* [TypingTweaks.](https://vencord.dev/plugins/TypingTweaks) Shows the avatar and role color in the typing indicator. Applicable even when multiple people are typing.
* [SearchReply.](https://vencord.dev/plugins/SearchReply) Adds a "Reply" button to messages in search.
* [ShikiCodeblocks.](https://vencord.dev/plugins/ShikiCodeblocks) Beautifully styles code blocks in VSCode style. Custom themes can be applied.
* [ShowAllMessageButtons.](https://vencord.dev/plugins/ShowAllMessageButtons) Enables displaying all buttons on the message action panel without needing to hold Shift.
* [ShowHiddenChannels.](https://vencord.dev/plugins/ShowHiddenChannels) Displays channels you don't have access to. Shows members (if it's a voice channel) and the date of the last message.
* [ShowTimeouts.](https://vencord.dev/plugins/ShowTimeouts) Displays user timeout icons in the chat regardless of access rights.
* [SilentMessageToggle.](https://vencord.dev/plugins/SilentMessageToggle) Adds a button for sending messages silently to the input panel (replaces manually adding *@silent* before each message).
* [SilentTyping.](https://vencord.dev/plugins/SilentTyping) Hides typing status. A toggle can be added to the right of the input field.
* [SortFriendRequests.](https://vencord.dev/plugins/SortFriendRequests) Sorts friend requests by received date; shows the date.
* [Translate.](https://vencord.dev/plugins/Translate) Translates messages via Google Translate.
* [TypingIndicator.](https://vencord.dev/plugins/TypingIndicator) Adds a typing indicator next to the channel avatar.
* [ValidUser.](https://vencord.dev/plugins/ValidUser) Corrects incorrect display of pings from unknown users.
* [ViewRaw.](https://vencord.dev/plugins/ViewRaw) Copies and views any message in Raw format.
* [VoiceMessages.](https://vencord.dev/plugins/VoiceMessages) Adds the ability to send audio in the form of voice messages.
* [VolumeBooster.](https://vencord.dev/plugins/VolumeBooster) Allows setting a user's call volume above the maximum.
* [WhoReacted.](https://vencord.dev/plugins/WhoReacted) Displays user avatars in the reaction area (like in Telegram).

### Themes

<details>

<summary>Installation via Vencord (easier)</summary>

Discord settings, Vencord section → Themes → Online Themes. Paste the direct link to the .css theme in the input field and switch tabs.

</details>

<details>

<summary>Installation via OpenAsar (better)</summary>

Discord settings → OpenAsar → Theming.  
1. Go to the repository of the desired theme.
2. In the repository search, enter `@import url`.
3. Find the main file in .css format, **which consists only of importing links to theme resources and settings.** If it's not among the files in the repository itself, look for it in the releases.
4. Copy the contents of the file into the input field of the Theming section.  

</details>

* [Dark Discord.](https://github.com/discord-modifications/dark-discord) Truly *dark* theme. Simple and unobtrusive. [Preview.](https://gibbu.github.io/ThemePreview/?file=https://discord-modifications.github.io/dark-discord/src/source.css) Direct link: `https://raw.githubusercontent.com/localip/dark-discord/main/DarkDiscord.theme.css`
* [Fluent Discord.](https://github.com/TakosThings/Fluent-Discord) A theme designed in the Microsoft Fluent Design style (like in Windows 11). [Preview.](https://raw.githubusercontent.com/TakosThings/Fluent-Discord/develop/images/ui-1.5.5.png)  
You can replace the app background with your own (according to your desktop wallpapers, for example). To do this, replace the contents in parentheses of the `--fluent-acrylic-background: url` parameter with the direct link to the image.

## 🎧 Spotify:
### Software
1. [Spicetify](https://github.com/spicetify/spicetify-cli) (recommended):
   * [Install Spicetify with Marketplace in one command.](https://github.com/spicetify/spicetify-marketplace/wiki/Installation)  
     Further installation is mainly done through the Marketplace menu → Extensions. This installation method implies automatic extension updates as updates are released.
   * Installing Spicetify adds a menu of experimental client features (without changing anything by default). Use with caution!  
   * For users without a Premium subscription → [Adblock.](https://github.com/CharlieS1103/spicetify-extensions/blob/main/adblock/README.md)

### Extensions and Apps

* [Full Screen Mode.](https://github.com/daksh2k/Spicetify-stuff/tree/master/Extensions/full-screen) Beautiful and aesthetic full-screen mode. To display lyrics, you need to activate [lyrics-plus.](https://github.com/spicetify/spicetify-cli/blob/master/CustomApps/lyrics-plus/README.md)
* [Play Next.](https://github.com/daksh2k/Spicetify-stuff/blob/master/EXTENSIONS.md#play-next) By default, the "Add to Queue" button puts the track at the end of the queue. This extension adds a button that allows you to place the song you select next (first) in the playback queue.
* [Section Marker.](https://github.com/Aimarekin/Aimarekins-Spicetify-Extensions/tree/main/section-marker) Adds markers to the playback timeline, dividing the track into sections based on mood and rhythm changes. Works with all tracks.
* [Imaged Folders.](https://github.com/SunsetTechuila/imaged-folders) Adds the ability to set custom images as covers for playlist folders.
* [Volume Percentage.](https://github.com/daksh2k/Spicetify-stuff/blob/master/EXTENSIONS.md#volume-percentage) Adds volume display in percentages next to the slider on the player panel.
* [Immersive View.](https://github.com/ohitstom/spicetify-extensions/tree/main/immersiveView) Adds a button that hides side panels, leaving only the current open page.
* [Scannables.](https://github.com/ohitstom/spicetify-extensions/tree/main/scannables) Spotify QR codes from the mobile client, opened via the context menu.
* [Image Opener.](https://github.com/Tetrax-10/Spicetify-Extensions/tree/master/Image-Opener) Adds the ability to open the full-size avatar/cover/banner image.
* [Show The Genres.](https://github.com/Delusoire/spicetify-extensions/tree/main/extensions/show-the-genres) Displays common genres associated with the artist's works in the player panel.
* [Copy Lyrics.](https://github.com/Aimarekin/Aimarekins-Spicetify-Extensions/tree/main/copy-lyrics) Ability to copy song lyrics in Karaoke mode.
* [Copy to Clipboard.](https://github.com/pnthach95/spicetify-extensions) Allows copying song titles.
* [Seek on scroll.](https://github.com/SunsetTechuila/seekonscroll) Scrolls through the track using the mouse wheel on the timeline.
* [Spicetify Stats.](https://github.com/harbassan/spicetify-stats) Displays statistics similar to [volt.fm.](https://volt.fm) Installation is done [manually.](https://github.com/harbassan/spicetify-stats#manual-installation)  

2. [SpotX](https://github.com/amd64fox/SpotX) (adblock for non-Premium users and activation of experimental features; installation either [automatic,](https://raw.githack.com/amd64fox/SpotX/main/Install_New_theme.bat) or through selecting the necessary flags [manually](https://github.com/amd64fox/SpotX/discussions/60)).  

### Useful

* [volt.fm.](https://volt.fm) Service for collecting and analyzing your listening statistics. Provides a huge amount of useful data on genres, categories, time intervals.  
* [Google spreadsheet with direct links to download offline installers for all versions of Spotify for Windows.](https://docs.google.com/spreadsheets/d/1wztO1L4zvNykBRw7X4jxP8pvo11oQjT0O5DvZ_-S4Ok/edit?pli=1#gid=0)
* [Script to block desktop client updates for Spotify.](https://github.com/amd64fox/Rollback-Spotify)
* [Complete removal of the Spotify client from the system.](https://github.com/amd64fox/Uninstall-Spotify)

## 🔧 CLI Utilities
>
> [!NOTE]
> For ease of use, the executable .exe needs to be placed in /system32, or the path to the file needs to be added to the PATH environment variables. [How to do it](https://remontka.pro/add-to-path-variable-windows/)  
Or install these utilities via Winget/Chocolatey/Scoop (recommended!).  

* [aria2c.](https://aria2.github.io/) Equivalent to wget, Download Master, and others. Supports torrents.
* [ffmpeg.](https://ffmpeg.org/) Audio and video file converter, with many features.
* [yt-dlp.](https://github.com/yt-dlp/yt-dlp) Video and audio downloader from YouTube, SoundCloud, PornHub, and [1838 other sites.](https://github.com/yt-dlp/yt-dlp/blob/master/supportedsites.md//) Recommended for use through Hitomi Downloader (see below in the Useful section).
* [payload-dumper-go.](https://github.com/ssut/payload-dumper-go) Quickly breaks down Android firmware payload.bin into individual images.
* [Revancify.](https://github.com/decipher3114/Revancify#installation) Convenient assembly and installation of ReVanced/ReVanced Extended via Termux.
* [Chocolatey.](https://community.chocolatey.org/) Package manager for Windows in the style of Linux apt/pacman. More powerful than built-in Winget.
* [Scoop.](https://scoop.sh/) Equivalent to Chocolatey. Unlike the latter, it installs programs not in the system, but in a separate user folder, some "semi-portable" versions that can be easily removed later. Cons: VERY slow cli search.

## ⏹ Scripts

* [Platform Tools Installer.](https://github.com/SunsetTechuila/Platform-Tools-Installer) Script automatically downloads the latest [Platform tools](https://developer.android.com/tools/releases/platform-tools) for your platform, prompts you to choose a location for unpacking, and then adds them to PATH.

## 🗂 Windows Interface Modification via .reg Files
* [Hide Desktop Shortcut Arrow.](https://t.me/begoniacommunity/1384476) Move the Blank.ico file to the Windows root folder and run RemoveArrow.bat; restart File Explorer. To revert the changes, run RestoreArrow.bat.
