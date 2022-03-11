# HP_250_G4-Hackintosh-EFI

EFI for HP 250 G4 -Intel i5 6200U- (OpenCore) -OutDated-

What works:
WiFi (itlwm) - Replaced the WiFi card for an intel one.
Speaker and AUX Jack.
Graphics Acceleration.
Integrated Camera.
USB 3.0 is working fine.
Brightness and keyboard brightness hotkeys (I did my own DSDT patch; you can use the newly released kext to do it automatically).
Battery Percentage.
Clock Frequency Response is also on point.

What is not working:
Bluetooth - It can work but it is blacklisted on the Bios (Reversed engineered the Bios and found a way to whitelist it but it requires a lot of hardware mods).
Fairplay DRM - Due to not having a dedicated GPU hence DRM issues occurs on sites like Netflix.


# ---Warning---
If you decide to change the wifi card then you should first disable the bluetooth option in the bios menu.
Also, if your laptop has only one antenna (One cable connected to the wifi card before replacing) then make sure you connect the only cable to the pin labeled "Main".
