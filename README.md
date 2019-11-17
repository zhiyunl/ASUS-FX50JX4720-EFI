# ASUS-FX50JX4720-EFI

 Backup EFI for my MAC

## Information

Mac OS version: 10.14.6

Clover version: r5098

Laptop: 

- Model: ASUS FX50JX
- CPU: i7-4720HQ
- RAM: 12GB DDR3L

![osinfo](/osinfo.png) 

## Functionality

- [x] Dynamic CPU frequency
- [x] Screen Brightness Adjustment, using F5/F6 Keybinding
- [x] Sleep and wakeup, using sleep mode 25
- [x] HD4600 Integrated Graphic Card, memory 2048MB
- [x] Battery Info
- [x] USB3.0/USB2.0 
- [x] Camera
- [x] HDMI output
- [x] wifi, changed to a natively working wifi card
- [x] Sound, using AppleALC, able to switch speaker and microphone automatically
- [x] HiDPI, using QuickRes

## Transfer to similiar Model Laptop
- In BIOS, enable Launch CSM and turn off Secure Boot
- In Clover, use [Clover Configurator.app](/Clover%20Configurator.app.7z)
   + Modify Macbook model number, choose the one with the nearest CPU frequency as your laptop
   + Generate serial number
   + Change memory ram size
   + Generate ssdt-alpf.aml using CPU-S, replace what's in ACPI/patched/, it's for dynamic CPU frequency 

# ENJOY!
