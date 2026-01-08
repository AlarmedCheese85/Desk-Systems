# 🛠️ Desk Systems Project
A collection of **hardware + software desk projects** designed to enhance productivity, provide system monitoring, and give your workspace a functional, industrial feel.  

This repository includes two main projects:

1. **Smart Desk Control Panel** – physical controls for your PC and desk.
2. **Physical Status Monitor** – a glanceable display for PC/server status.

Both projects combine **3D printing, electronics, and software** to create polished, usable desk hardware.

---

## 📋 Table of Contents
- [Project Overview](#project-overview)  
- [Project 1: Smart Desk Control Panel](#project-1-smart-desk-control-panel)  
  - [Goal](#goal)  
  - [Roadmap](#roadmap)  
- [Project 2: Physical Status Monitor](#project-2-physical-status-monitor)  
  - [Goal](#goal-1)  
  - [Roadmap](#roadmap-1)  
- [Repository Structure](#repository-structure)  
- [Future Expansion Ideas](#future-expansion-ideas)  
- [License](#license)

---

## Project Overview
These projects are designed to be:

- **Functional** – Not just desk toys; real input and monitoring tools.
- **Customizable** – Fully 3D-printable enclosures and open-source code.
- **Modular** – Each project can be used independently or combined into a single desk system.
- **Portfolio-ready** – Demonstrates hardware, software, and design integration.

---

## Project 1: Smart Desk Control Panel

### Goal
Create a **physical control module** for your desk that allows quick access to common PC/desk functions using buttons, rotary encoders, and switches.

### Roadmap

#### Phase 1 – Planning & Design
- Define desired features:
  - Power, mute, macro buttons
  - Rotary encoders for volume, brightness, fan speed
  - Optional status LEDs
- Choose microcontroller platform:
  - Arduino (HID/USB) or Raspberry Pi Pico
- Sketch layout of controls
- Define enclosure constraints (desk space, angle, cable routing)

#### Phase 2 – Hardware Prototype
- Wire buttons and encoders on a breadboard
- Test input reading with firmware
- Verify USB communication with PC
- Add debouncing and encoder logic
- Validate power requirements

#### Phase 3 – Firmware Development
- Input handling module
- USB HID or serial communication
- Configurable mappings (volume, keybinds)
- Error handling and recovery
- Commented and structured code

#### Phase 4 – Enclosure Design
- Design enclosure in Fusion 360
- Mounting points for microcontroller, buttons, and USB
- Print prototype enclosure
- Iterate fit and ergonomics
- Finalize print settings

#### Phase 5 – Integration & Polish
- Assemble final hardware
- Manage cables neatly
- Add labeling/icons
- Stress test inputs
- Document assembly process

#### Phase 6 – Documentation
- Wiring diagrams
- Firmware flashing instructions
- STL exports and print settings
- Troubleshooting section
- Future expansion ideas

---

## Project 2: Physical Status Monitor

### Goal
Create a **dedicated display** that shows PC/server status at a glance, with no overlays or clutter. Ideal for monitoring CPU, memory, network, or server uptime.

### Roadmap

#### Phase 1 – Planning & Architecture
- Choose data source:
  - Local PC, server, or network device
- Choose display type:
  - OLED, LCD, or HDMI screen
- Decide displayed metrics:
  - CPU usage, temperatures, RAM usage, network activity
- Define update rate and layout

#### Phase 2 – Data Collection
- Write monitoring script:
  - Python (psutil) or API-based
- Normalize and format data
- Test reliability over extended uptime
- Handle missing or invalid data

#### Phase 3 – Display Software
- Render UI layout
- Test font readability and color contrast
- Add status icons/graphs
- Implement startup and recovery behavior

#### Phase 4 – Hardware Integration
- Connect display to microcontroller or Raspberry Pi
- Test power stability
- Cable routing and strain relief
- Auto-start on boot

#### Phase 5 – Enclosure Design
- Design display housing
- Optimize viewing angle
- Optional wall or desk mount
- Ventilation considerations
- Print and fit test

#### Phase 6 – Assembly & Testing
- Full assembly of hardware
- Long-duration uptime testing
- Heat testing
- Cable strain relief
- Visual clarity testing at distance

#### Phase 7 – Documentation
- Setup instructions
- Software configuration
- Print settings
- Wiring diagrams
- Customization guide

## Future Expansion Ideas
- Web-based configuration tool
- Modular, interchangeable enclosures
- Network-based desk monitoring/control
- Multi-display support
- Open-source community-driven configurations

---

## License
This project is open-source. See the `LICENSE` file for details.

