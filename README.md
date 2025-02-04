# iMac-2011-Mojave

- Before you add these patches you need to use the dosdude1 Mojave patcher ➤ [the dosdude1 patcher](https://forums.macrumors.com/threads/macos-10-14-mojave-on-unsupported-macs-thread.2121473/)
- Although @dosdude1 had all patches in place within his own pather he never changed the patch sets according to the needs of this particular iMac Mid 2011 system. Installing Mojave will remain a two step process, first install via the dosdude1 patcher, apply the patches (except the legacy video patch) of his patcher and after the final reboot download and load this patches.

### Fix sleeping panics in macOS Mojave 10.14++
- Support Graphics Intel HD 3000.
- Support of new AMD Polaris and NVIDIA Kepler modded iMac Systems 

#### Warnings:
##### 1 :this package replaces system files in /S/L/E and could render your system unbootable.

#### How to download ready release package

On the right hand side of this [page](https://github.com/Ausdauersportler/iMac-2011-Mojave) there is a Releases [button](https://github.com/Ausdauersportler/iMac-2011-Mojave/releases/tag/v1.0) leading you to the download page.

#### How to download ready complete source and build the package

Just press on the Code button and select download zip. Within the zip there is a script called Package-Creator.command, just double click to buid the installer package from the sources.

This is a Fix for Graphics Intel HD 3000 and sleep on iMac 12,X for macOS Mojave 10.14.1 and later

Support Graphics Intel HD 3000 and Nvidia Kepler GPU and AMD Polaris/Ellesmere GPU

Within the Documents folder you will find pictures showing the package selection for each GPU type.

#### Installation selection for iMac systems with Kepler GPU needing OpenCore to provide brightness control:

This selection assumes the user will use OpenCore to enable brightness control. Applies to the following GPU: K610M, K1000M, K2000M, K1100M, K2100M, GTX675M, GTX770M and GTX788M (780M using Santa's Little Helper vBIOS).

![Modular Image Creation](https://github.com/Ausdauersportler/iMac-2011-Mojave/blob/main/Documentation/K610M-K1100M-K2100M.png)

#### Installation selection for iMac systems with AMD Polaris/Ellesmere GPU:

![Modular Image Creation](https://github.com/Ausdauersportler/iMac-2011-Mojave/blob/main/Documentation/MOJAVE-SLEEP-PATCH-AMD.png)

#### Installation selection for iMac systems with other Kepler GPU:

![Modular Image Creation](https://github.com/Ausdauersportler/iMac-2011-Mojave/blob/main/Documentation/MOJAVE-SLEEP-PATCH-NVIDIA.png)

#### Some more information:
[2011 iMac Graphics Card Upgrade](https://forums.macrumors.com/threads/2011-imac-graphics-card-upgrade.1596614/)

#### Installation details:
[Catalina Package Installer](https://forums.macrumors.com/threads/2011-imac-graphics-card-upgrade.1596614/page-421?post=29144691#post-29144691)

#### Credit:
- Fix/Patch: [dosdude1](https://forums.macrumors.com/members/dosdude1.669685/), [highvoltage12v](https://forums.macrumors.com/members/highvoltage12v.883629/)
- Tester: chris1111, [highvoltage12v](https://forums.macrumors.com/members/highvoltage12v.883629/), [Ausdauersportler](https://forums.macrumors.com/members/ausdauersportler.1199136/) 
- Packager: [Ausdauersportler](https://forums.macrumors.com/members/ausdauersportler.1199136/)

#### For ➣  [macOS Catalina 10.15.4 and later](https://github.com/Ausdauersportler/iMac-2011-Catalina)
### A macOS Package to activate the legacy video Intel HD 3000 to avoid sleep problems and activate H.264 on macOS Catalina
- Working for macOS Catalina 10.15.4 and later






