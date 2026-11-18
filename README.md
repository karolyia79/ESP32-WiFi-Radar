> [!IMPORTANT]
> **Manual Update Required from v0.1.8b and Earlier!**
> Due to repository restructuring and updated OTA endpoints (`ESP32-WiFi-Radar`), online auto-update will **not** work from `v0.1.8b` or older firmware versions.
> Please download `firmware.bin` below and upload it once manually via **WebUI → System → Actions → Manual Update**. All your saved settings (Wi-Fi, MQTT, Mesh, 3D Matrix) in EEPROM will be preserved. Starting from `v0.1.9b`, one-click online updates will work seamlessly.

# ESP32 WiFi Passive Radar

Modular, **ESP-NOW Mesh-capable** passive Wi-Fi presence and motion detection system with 3D spatial trilateration and native **Home Assistant MQTT Auto-Discovery** integration.

## Key Features
- **Passive CSI / RSSI Motion Detection:** Detects human presence and movement using existing Wi-Fi devices without extra wearable tags.
- **ESP-NOW Mesh Architecture:** Supports Standalone, Master Router (Hub), and Slave node topologies on a fixed Wi-Fi channel.
- **3D Spatial Matrix & Trilateration:** Real-time indoor/outdoor coordinate estimation with EMA smoothing and WebUI 3D visualization.
- **Home Assistant Integration:** Automatic MQTT entity discovery and configurable telemetry topics.
- **OTA Firmware Updates:** Supports both local `.bin` upload and direct online updates from GitHub Releases.

---
*Official firmware release repository. Compiled binaries and release notes are available under the **Releases** section.*
