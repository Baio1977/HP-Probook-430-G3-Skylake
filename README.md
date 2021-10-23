[![](https://img.shields.io/badge/Gitter%20Ice%20Lake-Chat-informational?style=flat&logo=gitter&logoColor=white&color=ed1965)](https://gitter.im/ICE-LAKE-HACKINTOSH-DEVELOPMENT/community)
[![](https://img.shields.io/badge/EFI-Release-informational?style=flat&logo=apple&logoColor=white&color=9debeb)](https://github.com/Baio1977/EFI-Varie-Hackintosh)
[![](https://img.shields.io/badge/Telegram-HackintoshLifeIT-informational?style=flat&logo=telegram&logoColor=white&color=5fb659)](https://t.me/HackintoshLife_it)
[![](https://img.shields.io/badge/Facebook-HackintoshLifeIT-informational?style=flat&logo=facebook&logoColor=white&color=3a4dc9)](https://www.facebook.com/hackintoshlife/)
[![](https://img.shields.io/badge/Instagram-HackintoshLifeIT-informational?style=flat&logo=instagram&logoColor=white&color=8a178a)](https://www.instagram.com/hackintoshlife.it_official/)

HP Probook 430 G3 to run macOS
============================================

- Bootloader version: Opencore 0.7.4
- macOS version: macOS Big Sur 11.6 (20G165)
- Windows version: Windows 11 Release

![infocatalina](./Screenshot/1.jpg)

![Oops!There was supposed to be an image here](https://i.imgur.com/8BIOnKE.png)

#### What works

- iGPU acceleration (Intel HD 520)
- Sleep
- Battery Percentage
- Display Brightness
- USB ports
- Internal Camera
- Audio with mute button (Both internal speakers and Microphone CX20724)
- Native Power Management/(Also with cpufriend)
- SMBus Controller
- WI-FI + BT Intel
- CPU Temperature Monitoring
- Fan Speed Monitoring
- VGA (*suprisingly*)
- Three Finger Gestures
- Boot Chime
- Dualbooting with Windows
- iMessage
- Facetime

#### Specs

| Component      | Brand                                                            |
|----------------|------------------------------------------------------------------|
| **CPU**        | `Intel Core i5-6200U `                                           |   
| **iGPU**       | `Intel HD Graphics 520 `                                         |
| **Audio**      | `Conexant 20724 - layout 3`                                      |
| **Ethernet**   | `Realtek RTL8111/8168`                                           |
| **OS**         | `macOS Big Sur 11.6 (20G165)` and `Windows`           |

#### USBMap
![infocatalina](./Screenshot/4.jpg)

#### Power
![infocatalina](./Screenshot/5.jpg)

#### HDMI 
![infocatalina](./Screenshot/6.jpg)

#### Making the Three Finger Gestures Work

- Open System Preferences->Keyboard->Shortcuts
![Oops!There was supposed to be an image here](https://i.imgur.com/pv0wnyy.png)
- Double-tap on shortcut you want it to perform.
- Do the Three Finger Gesture to set it.
- Voila! You're Done!

#### Benchmarks
- Geekbench 5 [Multi-core and Single core](https://browser.geekbench.com/v5/cpu/8013906)

#### Important
- In the config.plist, section `PlatformInfo > Generic`, the following fields are currently edited with CHANGEME. Please generate your own serial. 

- This repo can be helpful for other HP Probook/Elitebook series notebooks
 
### Bios Configuration

#### Enable
- Fast Boot
- Runtime Power Management
- Extended Idle Power States
- Deep Sleep
- Power Control
- Turbo Boost
- Virtualization Technology (VTx)
- Hyperthreading
- Multi Processor

 #### Disable 
- Legacy boot
- Wake when lid is opened
- Wake on USB

#### Having some problem
Create an issue and I'll try to help as many as I can

#### Credits
- [Apple](https://apple.com) for [macOS](https://www.apple.com/macos/big-sur/)
- [Acidanthera](https://github.com/Acidanthera) for [OpenCorepkg](https://github.com/acidanthera/OpenCorePkg) and necessary kexts
- [Krazy-Killa](https://github.com/Krazy-Killa) for the Three finger gestures
- [dortania](https://github.com/dortania) for its detailed guides

