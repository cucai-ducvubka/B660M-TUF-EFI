1. Updated to official version 0.8.3, supporting Catalina 10.15.x, bigsur 11.6.x, Monterey 12.x, MacOS 13 beta 5

2. Update Kexts to the latest version to support the newly sold heavy gunner sound card

3. The default config.plist supports all Navi core discrete graphics cards and their temperature monitoring (you need to check RadeonSensor.kext and SMCRadeonGPU.kext yourself, OS13 is no longer needed)

4. Boot the Broadcom wireless and Bluetooth that support PCIEx1 by default. The onboard intel WiFi&BT needs to use config-intelWIFI&BT.plist and rename it to config.plist to use

5. Re-customize 15 USB ports, keep the front USB (USB3+TYPE-C)

Added support for RX6650XT and RX6950XT, you need to check the corresponding SSDT patch in ACPI to enable it.