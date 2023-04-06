## Butterfly OHW Version

### Butterfly Nano
Create a special fully open source ultra-low cost hardware wallet platform with a high security hardware wallet for under $5. MCU runs Zephyr RTOS, MCU can use any Zephyr supported chip.

The Secure Element (SE) of hardware implementation supports ATECC608A chip. Software implementation Secure Element (SE) supports any MCU, using MCU built-in security.

| Software                                                     | Hardware                                                     |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [butterfly-firmware](https://github.com/Butterfly-OHW/butterfly-firmware) | [butterfly-hardware-modules](https://github.com/Butterfly-OHW/butterfly-hardware-modules) (optional) |



### Butterfly Pro
Use a low cost SOC, Many vendors offer ultra-low cost optimized SOCs, such as Allwinner D1s, Rockchip RK3308, etc. 

The Secure Element (SE) of hardware implementation supports ATECC608A chip. Software implementation Secure Element (SE) supports any Linux/BSD.

This version has an estimated hardware cost of $20.

| Software                                                     | Hardware                                                     |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [butterfly-os](https://github.com/Butterfly-OHW/butterfly-os) | [butterfly-hardware-modules](https://github.com/Butterfly-OHW/butterfly-hardware-modules) (optional) |

### Butterfly Ultra
Use OP-TEE this is an open source Trusted Execution Environment (TEE) implementing the Arm TrustZone technology. TEE technology has the same security as a standalone hardware security chip. 

This version runs Linux and uses Yocto to create custom Linux-based systems, SOCs can offer great performance and scalability. Some typical SBCs that can run OP-TEE include the Raspberry Pi 3B (BCM2837), Rock Pi 4 (Rockchip RK3399), BeagleBone AI (Texas Instruments AM5729), etc. 

The Secure Element (SE) of hardware implementation supports TrustZone (OP-TEE) and ATECC608A chip. Software implementation Secure Element (SE) supports any Linux/BSD. 

This version has an estimated hardware cost of $100.

| Software                                                     | Hardware                                                     |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [butterfly-os](https://github.com/Butterfly-OHW/butterfly-os) | [butterfly-hardware-modules](https://github.com/Butterfly-OHW/butterfly-hardware-modules) (optional) |

## Butterfly App

| Mobile                                                     | Desktop                                                     |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [butterfly-app-mobile](https://github.com/Butterfly-OHW/butterfly-app-mobile) | [butterfly-app-desktop ](https://github.com/Butterfly-OHW/butterfly-app-desktop) |


## Butterfly Info
The chips and hardware chosen for this project can be easily purchased from the market. No proprietary hardware or chips that are not publicly documented are used.

This project is developed in a completely open source way, including hardware PCB design and firmware, Android/iOS client, Windows/Linux/macOS client, etc.

WiFi and Bluetooth and USB support.

We want to be the first hardware wallet for everyone, and we operate as a completely open source and non-commercial approach. commercial products like Trezor, Ledger, etc. also require a minimum of $100. Other cold wallet approaches also require a completely offline phone. We want to lower the price barrier for hardware wallets. Make it possible for everyone to store and use digital currency securely.

