<div align="center">
  <img src="assets/whisper.png" alt="Whisper">
</div>

# Whisper

> Off-grid messaging for everyone. No internet, no cell towers, no limits.
WhisperOS is a LoRa mesh firmware built upon **MeshCore**. This core foundation means that WhisperOS inherits all of MeshCore's features and is fully compatible with it, serving as an advanced, user-friendly interface for the underlying mesh network.

**Core Functionality:**
*   **MeshCore Base:** All features supported by MeshCore are also supported by WhisperOS.
*   **LoRa Mesh Network:** Enables communication over a decentralized mesh network.

**User Interface and Display:**
*   **Home Screen:** Displays essential information at a glance, including a top status bar, battery percentage, user log name, and the current time (configurable via time zone settings). It also shows the number of received messages, a BLE pairing pin, basic frequency, Spreading Factor (SF), and device uptime.
*   **Messages Screen:** Lists all received messages. A long press on a message navigates to the next one.
*   **Nodes Page:** Shows a list of other devices ("nodes") on the network, which can be companions or repeaters.
*   **RF Page:** Provides detailed radio frequency information with a "fancy" bar graph display.
*   **GPS Page:** When a GPS module is present and enabled, this screen displays coordinates (latitude and longitude), altitude, and current speed.
*   **System Page:** Contains various settings to customize the device's behavior.

**Messaging Capabilities:**
*   **Public and Private Messaging:** Users can send messages to the public channel or directly to specific devices.
*   **Preset Quick Messages:** A list of predefined messages is available for quick communication.
*   **Free Text Messaging:** On devices with a joystick or other input methods, users can type custom messages.
*   **Multi-language Support:** The firmware supports a wide range of languages, including Chinese, Korean, Japanese, and Russian.

**Device Interaction and Tools:**
*   **Ping Feature:** Users can "ping" a repeater node to test connectivity. The result provides information on the time taken and, if both devices have GPS, the distance between them and the number of hops.
*   **Device Info Sharing:** An option in the RF page allows a user to send their device information to all other nodes on the network.
*   **Joysticks and Buttons:** The interface is navigable through button presses, long presses, and, on some devices, a joystick.

**System Settings and Customization:**
*   **Brightness Control:** The screen brightness can be adjusted (e.g., to medium) to conserve power.
*   **"Always On" Clock Face:** When there is no activity, the device can switch to a clock face that displays the time and date.
*   **Power Supply and Battery Calibration:** A feature allows users to calibrate the Analog-to-Digital Converter (ADC) for more accurate battery percentage readings. This is particularly useful for devices that do not have a fixed ADC from the factory. The process involves fully charging the device and then initiating the calibration from the system menu.
*   **Message Indicator:** An LED will continuously light up to notify the user of a new, unread message. This feature was suggested by the community. Devices with a buzzer or vibration motor will also provide alerts.
*   **BLE (Bluetooth Low Energy) Switch:** BLE can be toggled on or off.
*   **Time Zone Setting:** Users can set their local time zone.
*   **Reboot and Shutdown Options:** Standard options to restart or power off the device are available.


## 📥 Download

Get the latest firmware from https://ssaprus.works.

## 📱 Supported Devices

| Device | Notes |
|--------|-------|
| Heltec V3, V4, T114 | Full support |
| GAT562 Mesh Watch | Full support |
| GAT562 Trial Tracker | Full support |
| Wio Tracker L1 | Full support |
| MeshTiny | Full support |

## Get latest updates

https://t.me/whisper_dev

## The Fine Print 📝

- **Testing firmware only**: These builds are for testing and experimentation. Please test thoroughly before relying on them in critical situations
- **Backup your data**: Always backup your device configuration and data before installing
- **No warranty**: Provided as-is without guarantees. We recommend testing in your specific environment
- **Use responsibly**: Please ensure your use complies with local regulations. Users are responsible for their own compliance

## 🌐 Powered by MeshCore

[Learn more about MeshCore](https://github.com/meshcore-dev/MeshCore)
