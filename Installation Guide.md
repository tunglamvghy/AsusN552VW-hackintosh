# INSTALLATION GUIDE

***This repo works only on macOS 11 and above***
Before starting to install macOS, make sure your ***BIOS firmware version*** is ***300***, others will not work properly. If your BIOS is **not** 300, flash firmware file using file in /Debug/BIOS firmware followed by this [**turtorial**](https://youtu.be/DwJS8-GTgRU)

1. Make an installation USB using Olarila Image
2. Copy EFI in this repo to EFI partition of your USB
3. Boot the installation USB you've made and Install macOS on your SSD.
4. Boot to macOS you've installed
5. Using [**GenSMBIOS**](https://github.com/corpnewt/GenSMBIOS) or **OpenCore Configurator** to generate new SMBIOS
6. Copy **OC** folder and **Boot** folder from EFI partition of your USB to EFI partition of your SSD.
7. Restart and Enjoy your new hackintosh

***Notes:*** 
    
- *Change OpenCanopy background*
    1. You need a really big image! It seems this follows the same rules as any retina image, so you need an image double your resolution (3840x2160)
    2. Change the image to *PNG format*, rename it to *ModernBackground.png*
    3. Get [*chris1111/Icnspack-Builder*](https://github.com/chris1111/Icnspack-Builder) and install then launch the app.
    4. Click run. Drop your image on Icnspack-Builder. Click ready. Click save and save it somewhere.
    5. You should now have a resources.zip folder. Unzip that thing!
    6. Inside the folder should be Background.icns, put that into EFI/OC/Resources/Image
    7. Reboot and make sure it works
    
- If your pc has different specs, try to read [**OpenCore guide**](https://github.com/acidanthera/OpenCorePkg/blob/master/Docs/Configuration.pdf) or [**Dortania guide**](https://dortania.github.io/OpenCore-Desktop-Guide/installer-guide/) for more details

## Need help. Contact me
[![Telegram](https://img.shields.io/badge/Chat_on-Telegram-blue.svg)](https://t.me/tunglamvghy)
[![Messenger](https://img.shields.io/badge/Chat_on-Messenger-0078FF)](https://m.me/k38b.lamtung)
***Due to COVID-19, now I have free time. So if you want me to create your own EFI with a little payment, contact me via Telegram.***

## [Donate me](https://paypal.me/vtlam98)
If you want to donate, send me via [**PayPal**](https://paypal.me/vtlam98)
