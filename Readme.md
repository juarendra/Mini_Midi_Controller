# MIDI CONTROLLER CUSTOM
This is MIDI CONTROLLER Combine with Macropad. Midi controller is for sending midi key to computer, ussually usage for remix musi on DAW Software. Macropad usage to sending macro key that register on QMK/VIA Firmware. there are 2 Microcontroller on this Project, All Microcontroller using Pro Micro and Connected with USB HUB inside Case. Macropad is installed QMK/VIA Firmware and Midi Controller is installed using Arduino Framework. For Button Midi Controller we use Arcade Button and there are 2 RGB LED on each Arcade Button and For Macropad we use MX Mechanical Switch with RGB on South Face.

For Case, we use 3D print that you can download on [this folder](https://github.com/juarendra/Midi-Controller-Custom/tree/main/HARDWARE/3DCASE). You can print this if you want to build this Project. For Firmware you can find in [this folder](https://github.com/juarendra/Midi-Controller-Custom/tree/main/Firmware).

## Spesification
- 2 x Atmega32u4 Pro Micro
- 1 x USB HUB minimal 2 Port
- 16 x Button Arcade with Transparant Frame + 2 RGB each Button
- 5 x Mechanical MX Switch and Keycaps + 1 RGB per key
- 5 x Hotswap Switch
- 1 x Encoder 
- 1 x USB Type B Female
- Macropad Compatible With VIA

for Connection from Pro Micro to all Button and RGB you can use Connector and skun, 

## Preview Hardware
<p align="center">
  <img src="DOC/MidiController_1.png" width="50%" height="50%">
  <img src="DOC/MidiController_4.png" width="50%" height="50%">
  <img src="DOC/MidiController_5.png" width="50%" height="50%">
</p>

## Documentation Sensor V4
- [Dimension Sensor V4](https://github.com/juarendra/Midi-Controller-Custom/blob/main/HARDWARE/Dimension_MidiController.pdf)
- [JSON File For VIA](https://github.com/juarendra/Midi-Controller-Custom/blob/main/MidiController.json)

## BOM
| Item  | QTY |
| ------------- | ------------- |
| Arduino Pro Micor  | 2  |
| Arcade Button with transparant Frame 30mm | 16  |
| Switch Mechanical MX  | 5  |
| Keycaps Mechanical MX  | 5  |
| EC11 Rotary Encoder + Knob| 1  |
| Hotswap PCB Mechanical MX with LED RGB | 5  |
| RGB LED for Arcade Button | 32  |
| USB HUB minimal 2 Port | 1  |
| USB FEMALE type B | 1  |
| Wire and Skun | some  |

## FLASH FIRMWARE
- Flash QMK with QMK tollbox, the file you can find in [this link](https://github.com/juarendra/Midi-Controller-Custom/blob/main/Firmware/Macropad/25keys_cassette42_default.hex)
- Flash Midi Controller with arduino ,you need to install all library arduino, the file you can find in [this link](https://github.com/juarendra/Midi-Controller-Custom/blob/main/Firmware/MidiController/MidiController.ino)








