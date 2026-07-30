# CXD-ROUTER

CXD-ROUTER is a high-speed, modular router built on a Rockchip RK3588 SoC, powered by USB-C PD.

Most consumer routers are locked down and hard to upgrade. I built this to have a high-performance router where networking hardware (e.g., Wi-Fi modules) can be easily upgraded using M.2 slots without replacing the entire device.

## Specifications and Features

| Component | Details |
| :--- | :--- |
| **SoC** | Rockchip RK3588 |
| **Memory** | Onboard LPDDR4 memory |
| **Storage** | Onboard eMMC storage |
| **Upgradable Modules** | M.2 slots for 2.5GbE Ethernet and BE3600 Wi-Fi cards |
| **Power** | USB-C Power Delivery (PD) 12V |
| **I/O** | Mini HDMI, USB-C, 2.5G RJ45 |

## Firmware & Flashing

1. Follow Firefly's existing documentation to flash the RK3588 board:
   [Firefly ROC-RK3588-PC Upgrade Firmware Guide](https://wiki.t-firefly.com/en/ROC-RK3588-PC/upgrade_firmware.html)
2. Insert your M.2 2.5GbE Ethernet and BE3600 Wi-Fi cards into the board.
3. Connect a USB-C PD compatible power source to the board.
4. Plug your network cable into the 2.5GbE port.

## Images

* **PMIC:**
* **Housing:**

## Bill of Materials


---

*Initially inspired by Tomaž Zaman's 10G router.*
