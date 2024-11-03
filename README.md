# OpenWrt for Ruijie EW1200G Pro

## Introduction
The Ruijie EW1200G Pro is a popular router, and installing OpenWrt can enhance its functionality with additional features and customizations. This project provides step-by-step instructions and resources to help users install OpenWrt safely and effectively.

## Requirements
- Ruijie EW1200G Pro router
- A computer with access to the router
- Ethernet cable
- OpenWrt firmware file compatible with the Ruijie EW1200G Pro

## Installation Guide

### 1. Download OpenWrt Firmware
- Visit the [OpenWrt firmware download page]([https://downloads.openwrt.org/] (https://downloads.openwrt.org/snapshots/targets/ramips/mt7621/)) and find the appropriate firmware for the EW1200G Pro.

### 2. Connect to the Router
- Use an Ethernet cable to connect your computer to one of the LAN ports on the EW1200G Pro.

### 3. Access the Router's Admin Interface
- Open a web browser and enter the router's IP address (default is usually `192.168.110.1`).
- Log in with your admin credentials.

### 4. Backup Current Configuration (Optional)
- It's always a good idea to back up your current settings before flashing new firmware.

### 5. Flash OpenWrt
- Navigate to the firmware upgrade section in the router's admin interface.
- Upload the OpenWrt firmware file and start the upgrade process.
- Wait for the router to reboot.

### 6. Access OpenWrt
- Once the router has rebooted, you should be able to access the OpenWrt interface at `192.168.1.1`.

## Troubleshooting
- If the router does not boot after flashing, you may need to perform a hard reset.
- If you cannot access the OpenWrt interface, check your Ethernet connection and IP settings.

## Contributing
Contributions are welcome! If you have suggestions or improvements, feel free to fork the repository and submit a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
