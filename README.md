# Pixsso

![[Pixsso]([Images/Pixsso - hero.jpg](https://github.com/hal9ai/pixsso/blob/a66a24ea3226146af4a9c50274ca91fddd1ede3c/Images/Pixsso%20-%20hero.jpg))](https://github.com/hal9ai/pixsso/blob/a66a24ea3226146af4a9c50274ca91fddd1ede3c/Images/Pixsso%20-%20hero.jpg)

Pixsso is an open-source **eInk frame** that displays AI-generated images. Unlike other eInk displays, Pixsso features built-in buttons that allow you to interact with AI "artists" and shuffle through new images every day. Each AI artist is a multi-agent system that generates unique visuals based on different data inputs, such as real-time weather, news, or pop culture.

## Features
- 🖼 **AI-generated art**: Discover daily images created by AI-powered "artists."
- 🎛 **Interactive controls**: Use physical buttons to shuffle through different images.
- 📡 **Wireless updates**: Images are fetched automatically via WiFi.
- 🛠 **Open-source hardware**: Build your own Pixsso using the provided CAD files, BOM, and schematics.
- 🔋 **Battery-powered**: Runs on a 2000mAh battery for a low-power, minimalist experience.

## Hardware
Pixsso is built using:
- **Display**: Waveshare 7.5-inch monochrome eInk
- **Microcontroller**: ESP32
- **Battery**: 2000mAh LiPo
- **Custom parts**: 3D-printed and laser-cut components

### Build Your Own Pixsso
Pixsso's hardware is **open-source**. Here’s what you need to build it:
1. Order the components (available from Amazon & Waveshare)
2. 3D-print and laser-cut the required parts
3. Download the firmware binary from this repository and flash it onto the ESP32
4. Connect to WiFi and start generating AI images!

> **Note:** Check the folders for design files, BOM, and assembly instructions.

## Firmware
While the firmware source code is **not** open-source, we provide a **pre-compiled binary** that you can flash onto the ESP32.

### Flashing the Firmware
1. Download the latest firmware binary from the `firmware/` folder.
2. Use **esptool.py** to flash the binary to your ESP32:
   ```sh
   esptool.py --chip esp32 --port /dev/ttyUSB0 write_flash -z 0x1000 firmware.bin
   ```
3. Restart the device and follow the setup instructions.

## Pre-Orders
Want a **pre-assembled Pixsso**? You can pre-order one at [pixsso.com](https://pixsso.com), shipping begins in April 2025.

## Contribution
Contributions are welcome for:
- Improving the **CAD designs**
- Refining the **assembly instructions**

## License
Pixsso’s **hardware** is licensed under the **MIT License**, meaning you’re free to use, modify, and distribute it.

🚀 **Happy building!**

---

🛠 **Work in Progress**
This project is still a work in progress, and we will be adding more information in the coming days. Stay tuned!

