<div align="center">
  <img src="assets/whisper.png" alt="Whisper">
</div>

# WhisperOS

> Off-grid messaging for everyone. No internet, no cell towers, no limits.

WhisperOS is a LoRa mesh firmware built on **MeshCore**. By leveraging this foundation, WhisperOS inherits all MeshCore features while providing an advanced, user-friendly interface on top of the decentralized mesh network.

---

## Core Functionality

* **MeshCore Integration:** WhisperOS supports everything MeshCore supports—full compatibility included.
* **LoRa Mesh Networking:** Enables robust, decentralized communication across long distances.

---

## User Interface & Display

* **Home Screen:** Shows key information at a glance—status bar, battery percentage, user log name, current time (with time-zone settings), received message count, BLE pairing pin, frequency, spreading factor (SF), and device uptime.
* **Messages Screen:** Lists all received messages; long-pressing a message opens the next one.
* **Nodes Page:** Displays all visible nodes (companions or repeaters) in the network.
* **RF Page:** Provides detailed RF data with a clean bar-graph visualization.
* **GPS Page:** When a GPS module is available, shows latitude, longitude, altitude, and speed.
* **System Page:** Access all device settings and customization options.

---

## Messaging Capabilities

* **Public & Private Messaging:** Send to a public channel or directly to a specific device.
* **Preset Quick Messages:** Fast communication through predefined messages.
* **Free Text Messaging:** Supported on devices with a joystick or equivalent input.
* **Multi-Language Support:** Includes Chinese, Korean, Japanese, Russian, and more.

---

## Device Interaction & Tools

* **Ping Test:** Check connectivity with any repeater node. If GPS is enabled on both sides, distance and hop count are included.
* **Device Info Broadcast:** Option in the RF page to share your device info with all nodes.
* **Controls:** Navigate using buttons, long-press actions, and joysticks (where applicable).

---

## System Settings & Customization

* **Brightness Control:** Adjust display brightness to save power.
* **Always-On Clock:** When idle, the device can show a minimal clock face with time and date.
* **Battery Calibration:** Recalibrate the ADC for accurate battery readings (useful for devices without factory-set ADC values). Fully charge, then run calibration from the system menu.
* **New Message Indicator:** LED lights persistently for unread messages; buzzer/vibrator alerts also supported on compatible devices.
* **BLE Toggle:** Turn Bluetooth Low Energy on or off as needed.
* **Time Zone Setting:** Set your local time zone directly from the system menu.
* **Reboot / Shutdown:** Standard power management options.

---

## 📥 Download

Get the latest firmware at **[https://ssaprus.works](https://ssaprus.works)**.

---

## 📱 Supported Devices

| Device               | Notes        |
| -------------------- | ------------ |
| Heltec V3, V4, T114  | Full support |
| GAT562 Mesh Watch    | Full support |
| GAT562 Trial Tracker | Full support |
| Wio Tracker L1       | Full support |
| MeshTiny             | Full support |

---

## 🔔 Get Updates

Join the development channel: **[https://t.me/whisper_dev](https://t.me/whisper_dev)**

---

## The Fine Print 📝

* **Testing firmware only:** These builds are experimental—please test thoroughly before real-world use.
* **Backup your data:** Always back up configuration and messages before installing new firmware.
* **No warranty:** Provided as-is with no guarantees. Test in your intended environment.
* **Use responsibly:** Ensure compliance with local radio regulations. You are responsible for lawful use.

---

## 🌐 Powered by MeshCore

[Learn more about MeshCore](https://github.com/meshcore-dev/MeshCore)
