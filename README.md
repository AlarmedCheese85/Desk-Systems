📌 Project 1: Smart Desk Control Panel
🎯 Goal

Create a physical control module with buttons, knobs, and switches to control common desk and PC functions without relying on on-screen menus.

🧭 Roadmap
Phase 1 – Planning & Design

 Define features:

Buttons (power, mute, macros)

Rotary encoders (volume, brightness, fan speed)

Optional status LEDs

 Choose platform:

Arduino (HID / USB)

Raspberry Pi Pico

 Sketch control layout

 Define enclosure constraints (desk space, angle, cable routing)

Phase 2 – Hardware Prototype

 Wire buttons and encoders on breadboard

 Test input reading in firmware

 Verify USB communication with PC

 Add debouncing and encoder logic

 Validate power requirements

Phase 3 – Firmware Development

 Input handling module

 USB HID or serial communication

 Configurable mappings (volume, keybinds)

 Error handling and recovery

 Commented and structured code

Phase 4 – Enclosure Design

 Design enclosure in Fusion 360

 Mounting points for:

PCB / microcontroller

Buttons / encoders

USB strain relief

 Print prototype enclosure

 Iterate fit and ergonomics

 Finalize print settings

Phase 5 – Integration & Polish

 Assemble final hardware

 Cable management

 Labeling or icons

 Stress test inputs

 Document assembly process

Phase 6 – Documentation

 Wiring diagrams

 Firmware flashing instructions

 STL export and print settings

 Troubleshooting section

 Future expansion ideas

📊 Project 2: Physical Status Monitor
🎯 Goal

Create a dedicated, glanceable hardware display that shows system or server status information in real time.

🧭 Roadmap
Phase 1 – Planning & Architecture

 Decide data source:

Local PC

Server

Network device

 Choose display type:

OLED / LCD / HDMI screen

 Define displayed metrics:

CPU usage

Temperatures

RAM usage

Network activity

 Decide update rate and layout

Phase 2 – Data Collection

 Write system monitoring script:

Python (psutil)

API-based monitoring

 Normalize and format data

 Test reliability over long uptime

 Handle missing / invalid data

Phase 3 – Display Software

 Render UI layout

 Font and readability testing

 Color / contrast tuning

 Status icons or graphs

 Startup and recovery behavior

Phase 4 – Hardware Integration

 Connect display to controller

 Test power stability

 Cable routing tests

 Auto-start on boot

Phase 5 – Enclosure Design

 Design display housing

 Viewing angle optimization

 Wall / desk mount options

 Ventilation considerations

 Print and fit test

Phase 6 – Assembly & Testing

 Full assembly

 Long-duration uptime testing

 Heat testing

 Cable strain relief

 Visual clarity testing at distance

Phase 7 – Documentation

 Setup instructions

 Software configuration

 Print settings

 Wiring diagrams

 Customization guide
