# Latest Releases
## 🌀 Virtual Shifting (VS) support for:
### *Older* Wahoo KICKR
- 🆕 **([Kickr-Virtual-Shifting Library](https://github.com/Berg0162/Kickr-Virtual-Shifting))** Virtual Shifting for legacy Wahoo KICKR Smart trainers that are deprived of Wahoo VS-enabling firmware update(s)
- 🆕 **([Kickr-Dongle-VS](https://github.com/Berg0162/Kickr-Dongle-VS))** Virtual Shifting for older Wahoo KICKR Smart trainers using LilyGo T-Dongle-S3 and Kickr-Virtual-Shifting library
### *Older* Garmin Tacx
- 🆕 **([Tacx-Virtual-Shifting Library](https://github.com/Berg0162/Tacx-Virtual-Shifting))** Virtual Shifting for legacy Tacx Smart trainers that are deprived of the Tacx VS-enabling firmware update
- 🆕 **([Tacx-Dongle-VS](https://github.com/Berg0162/Tacx-Dongle-VS))** Virtual Shifting for older Tacx Smart trainers using LilyGo T-Dongle-S3 and Tacx-Virtual-Shifting library
### *Modern* Trainers (Elite, JetBlack, Wahoo and Garmin/Tacx)
- 🆕 **([Simcline-V2](https://github.com/Berg0162/Simcline-V2))** The latest Simcline-V2 version adds support for **Zwift Virtual Shifting**, enabling Simcline actuation when Virtual Shifting is active.
> **Important:** Zwift Virtual Shifting support requires a *modern* trainer running the firmware that explicitly supports the **Zwift Virtual Shifting** protocol.

## Featured Projects: Virtual Steering
These projects allow users to explore a range of input devices for **steering control in virtual cycling worlds**. The emphasis is on **enhancing interactivity and user experience** through both **accessible** and **innovative** control methods.

| HID Focus | Bluefruit Repository | Bluedroid/NimBLE Repository |
|-----------|-------------------|----------------------|
| Buttons, Joysticks, Rotary Encoders | [`OVS-DiscreteHIDs-Bluefruit`](https://github.com/Berg0162/Open-Virtual-Steering-DiscreteHID-Bluefruit) | [`OVS-DiscreteHIDs`](https://github.com/Berg0162/Open-Virtual-Steering-DiscreteHID) | 
| Turn & lean-based steering with MPU6050 | [`OVS-MotionIMU-Bluefruit`](https://github.com/Berg0162/Open-Virtual-Steering-MotionIMU-Bluefruit) | [`OVS-MotionIMU`](https://github.com/Berg0162/Open-Virtual-Steering-MotionIMU) |
| Voice-activated steering with TinyML | ℹ️ | [`OVS-VoiceControl`](https://github.com/Berg0162/Open-Virtual-Steering-VoiceControl) | 
> ℹ️ The **VoiceControl** project is tightly coupled to the **XIAO ESP32S3 Sense**, which includes a built-in microphone and supports only **ESP BLE-Hosts**. A Bluefruit version is not applicable.

The above projects use one of the 3 following *server libraries* that each support different Bluetooth stacks:<br>
🔹 **[BLE Steering Server](https://github.com/Berg0162/BLE-Steering-Server)** – For use with **Arduino-ESP32 core** (a.k.a Bluedroid)<br>
🔹 **[NimBLE Steering Server](https://github.com/Berg0162/NimBLE-Steering-Server)** –  For use with **ESP-NimBLE v2.x**<br>
🔹 **[Bluefruit Steering Server](https://github.com/Berg0162/Bluefruit-Steering-Server)** – For use with **Adafruit Bluefruit (Nordic's nRF52)**<br>
