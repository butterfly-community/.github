## Butterfly

### Things

Some small works combining software and hardware.

| Repo                                                     | Info                                                     |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [water-heater](https://github.com/butterfly-communtiy/water-heater) | This open-source solution for a water heater replaces the original controller to enable remote smart control.|

### Butterfly OHW Nano

A cheaper hardware wallet, the cost is less than $ 1. Support WiFi Bluetooth communication and optional screens.

Leverage Zephyr RTOS to support diverse microcontrollers from multiple vendors, mitigating vendor lock-in risks. Implement Bluetooth and Wi-Fi functionality on Espressif ESP32 series chipsets.

| Software                                                     |
| ------------------------------------------------------------ |
| [butterfly-ohw-firmware]([https://github.com/butterfly-communtiy/meta-butterfly-ohw-os](https://github.com/butterfly-communtiy/butterfly-ohw-firmware)) |

### Butterfly OHW Ultra

The Butterfly OHW Ultra utilizes OP-TEE, an open-source Trusted Execution Environment (TEE) that implements the Arm TrustZone technology. TEE technology offers security on par with standalone hardware security chips.

This version runs on Linux and employs Yocto to create custom Linux-based systems. SoCs deliver exceptional performance and scalability. Some typical Single Board Computers (SBCs) capable of running OP-TEE include the Raspberry Pi 3B (BCM2837), Rock Pi 4 (Rockchip RK3399), and BeagleBone AI (Texas Instruments AM5729).

The estimated hardware cost for this version is $100.

| Software                                                     | Hardware                                                     |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [meta-butterfly-ohw-os](https://github.com/butterfly-communtiy/meta-butterfly-ohw-os) | [butterfly-ohw-hardware](https://github.com/butterfly-communtiy/butterfly-ohw-hardware)|


The chips and hardware selected for this project can be easily sourced from the market, with no proprietary hardware or undocumented chips being used.

The project is developed entirely in an open-source manner, including hardware PCB design, firmware。

Support is provided for Wi-Fi, Bluetooth, and USB.

Last year, while engaged in a project involving OP-TEE and Yocto, I recognized that harnessing these technologies to develop a potent, scalable, and open-source hardware wallet would be remarkably fitting.
