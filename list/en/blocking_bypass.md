# 🚫 Circumventing Blocks:

### VPN
* [**Setting up your own server for VPN needs.**](https://github.com/begoniacommunity/unrestrict) It's paid (not expensive at all), but reliable. We recommend using Promo (~110 rubles/month) or Shared (~500 rubles/month) hosting plans from [aéza.](https://aeza.net/)

### GoodbyeDPI
Smart circumvention of deep packet inspection (DPI) systems.
1. [Download the latest version of GoodbyeDPI for Windows from the releases page.](https://github.com/ValdikSS/GoodbyeDPI/releases)
2. Move the folder to any location on the disk, from where we won't delete the folder in the future.
3. Get fresh lists:
   * For VPN, go to [antizapret.prostovpn.org/domains-export.txt](https://antizapret.prostovpn.org/domains-export.txt) and save the file to the previously downloaded folder, naming it `russia-blacklist.txt`.
4. Depending on your preferences, run as administrator:
   * `service_install_russia_blacklist.cmd`
   * `service_install_russia_blacklist_dnsredir.cmd` with DNS resolver redirection to Yandex DNS.

This will install the GoodbyeDPI service in Windows, and it will start automatically with the system. It doesn't interfere with VPN operation. To remove, use `service_remove.cmd`.  
[Options for other platforms](https://github.com/ValdikSS/GoodbyeDPI#similar-projects)  
[More information in the profile repository](https://github.com/ValdikSS/GoodbyeDPI#how-to-use)
<details>

<summary>Other</summary>

### Tor
In short, Tor can be described as a huge system of proxy servers that allows establishing anonymous network connections from anywhere on the Internet.
* [Tor Browser.](https://tor.calyxinstitute.org/download/) The simplest and most obvious use case of Tor in the form of a branded browser, also including various levels of protection against trackers and other tracking methods.
* [Tor Bridges.](https://bridges.torproject.org/) Request bridges to circumvent Tor network blocking (necessary for Russia). Bridges can be obtained via email by sending a blank email to bridges@torproject.org (only from Gmail accounts).
* [Tor Control Panel.](https://github.com/abysshint/tor-control-panel/blob/main/README.ru.md#readme-top) Management and monitoring of the Tor network on Windows (Tor Expert Bundle).

### Proxy
Lists of free proxies. It's better to use them as a last resort.
* [hidemyname](https://hidemy.io/ru/proxy-list/)  
* [SPYS.ONE](https://spys.one/)

### MTProto for Telegram
* [MTProxyStar.](https://t.me/MTProxyStar) Fresh proxies. Low ping, stable performance.

### Messengers
>
> At the moment, this section is positioned as "just in case." Here will be listed the most viable methods of secure communication in case if "Cheburnet" becames reality.
  
* [Briar.](https://briarproject.org/) Exchange encrypted messages through Tor network, local Wi-Fi, or Bluetooth.
* [Delta Chat.](https://delta.chat/ru/) Exchange encrypted messages via email, where [Autocrypt is supported.](https://autocrypt.org/dev-status.html) The application's interface is presented as a standard messenger. [More details here.](https://delta.chat/ru/help)

</details>
