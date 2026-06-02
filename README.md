
<h1 align="center">Hi, I'm Karan Gandhi</h1>

<p align="center">
  <b>Embedded Firmware Engineer | Ex-Qualcomm | Linux Drivers | STM32 / FreeRTOS | BLE | CAN | Bootloaders | TinyML & AI-Assisted Embedded Engineering</b>
</p>

<p align="center">
  I build embedded systems projects that sit close to the hardware-software boundary.
  <br/>
  My focus is firmware, drivers, RTOS-based systems, communication interfaces, debugging workflows, and documentation-first engineering.
</p>

<p align="center">
  <a href="https://github.com/karangandhi-projects">GitHub</a> ·
  <a href="https://www.linkedin.com/in/karangandhi0210/">LinkedIn</a>
</p>

---

## About Me

I am an Embedded Firmware Engineer with experience in modem software, power management, RTOS-based systems, debugging, and low-level firmware development.

Previously, I worked at **Qualcomm Technologies** on modem clock and power management software, where I contributed to firmware-level changes, crash log analysis, debugging workflows, and cross-functional bring-up support across software, hardware, RF, systems, and test teams.

Today, I am building hands-on embedded projects around:

- STM32 and ESP32-class microcontrollers
- FreeRTOS and custom RTOS concepts
- Linux kernel modules and virtual drivers
- CAN, UART, SPI, I²C, and BLE
- Bootloaders and firmware update foundations
- Sensor nodes and edge intelligence
- Spec-driven embedded project documentation
- AI-assisted engineering workflows for embedded systems

I care about building systems that are not only functional, but also understandable, testable, debuggable, and documented well enough for another engineer to continue from them.

---

## Current Focus

<table>
  <tr>
    <td width="50%" valign="top">

### Embedded Firmware

- STM32 HAL and FreeRTOS
- Bare-metal firmware concepts
- Interrupts, timers, GPIO, DMA fundamentals
- UART, SPI, I²C, CAN
- Bootloaders and memory maps
- Firmware architecture and modular drivers
- Debug logging and CLI-based observability

    </td>
    <td width="50%" valign="top">

### Linux / Drivers

- Linux kernel modules
- Character device drivers
- Virtual Ethernet drivers
- `net_device` driver model
- TX/RX queues and ring buffers
- NAPI concepts
- Kernel/user-space interfaces
- Debugging with logs, tools, and packet captures

    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">

### BLE & Edge Intelligence

- ESP32-C3 development
- BLE peripheral design
- GATT services and characteristics
- NimBLE stack fundamentals
- Sensor data publishing
- OLED-based embedded UI
- TinyML and edge anomaly detection concepts

    </td>
    <td width="50%" valign="top">

### AI-Assisted Engineering

- Spec-driven development
- Requirements and architecture documents
- Test planning and validation documents
- Debugging playbooks
- Agentic engineering workflows
- MCP and engineering harness concepts
- Embedded-focused knowledge bases

    </td>
  </tr>
</table>

---

## Highlighted Projects

### [vnet-driver](https://github.com/karangandhi-projects/vnet-driver)

A phase-based Linux virtual Ethernet driver using `vnet0`.

This project is focused on understanding how Linux network drivers are structured and debugged. It includes TX/RX paths, ring buffers, NAPI-style polling, ethtool support, statistics, documentation, CI, and a structured roadmap.

**Tech:** `C`, `Linux Kernel`, `net_device`, `NAPI`, `ethtool`, `Kernel Modules`, `CI`

---

### [stm32-smart-sensor-hub](https://github.com/karangandhi-projects/stm32-smart-sensor-hub)

A modular sensor hub built around STM32 firmware architecture.

The project focuses on clean driver abstraction, sensor interfaces, UART logging, CLI-based observability, and a firmware structure that can grow toward a production-style embedded system.

**Highlights:**

- Sensor abstraction layer
- I²C and SPI backends
- UART logging and CLI interface
- Cooperative task structure
- Low-power-aware sampling design
- Phase-based documentation

**Tech:** `Embedded C`, `STM32 HAL`, `I²C`, `SPI`, `UART`, `GPIO`, `Low-Power Firmware`

---

### [mini-ecu-v2](https://github.com/karangandhi-projects/mini-ecu-v2)

A virtual automotive ECU built on STM32F446RE.

This project uses FreeRTOS, CAN loopback communication, UART CLI, logging, and a bootloader-oriented structure. It is designed as a foundation for realistic ECU-style firmware, OTA experiments, and firmware update flows.

**Tech:** `C`, `STM32 HAL`, `FreeRTOS`, `CAN`, `UART`, `Bootloader Design`, `CI`

---

### [stm32-virtual-vehicle-ecu](https://github.com/karangandhi-projects/stm32-virtual-vehicle-ecu)

A modular STM32F4 virtual vehicle ECU with FreeRTOS, CAN communication, UART CLI, and a simple vehicle model.

The focus is clean separation between drivers, RTOS tasks, application logic, and simulated vehicle behavior.

**Tech:** `C`, `STM32F4`, `FreeRTOS`, `CAN`, `UART`, `Embedded Architecture`

---

### [ble-environmental-sensor-node](https://github.com/karangandhi-projects/ble-environmental-sensor-node)

A spec-driven BLE environmental sensor node using ESP32-C3, NimBLE, and a small OLED display.

The goal of this project is to learn BLE from an embedded systems perspective, including GATT design, peripheral behavior, sensor data publishing, local display output, and project documentation that can guide both humans and AI agents.

**Tech:** `ESP32-C3`, `NimBLE`, `BLE GATT`, `OLED`, `Sensor Nodes`, `Embedded C/C++`

---

### [Pseudo-Character-Device-Driver](https://github.com/karangandhi-projects/Pseudo-Character-Device-Driver)

A Linux pseudo character device driver implementing common file operations such as open, close, read, write, and lseek.

This project is useful for understanding Linux driver lifecycle, file operation callbacks, and kernel/user-space interaction.

**Tech:** `C`, `Linux Kernel`, `Character Drivers`, `File Operations`

---

### [bluetooth-audio-manager-linux](https://github.com/karangandhi-projects/bluetooth-audio-manager-linux)

A Linux utility created to fix and toggle Bluetooth audio profiles, especially A2DP/HFP issues on PipeWire-based systems.

This project came from a real usability problem and focuses on scripting, automation, and practical Linux troubleshooting.

**Tech:** `Shell`, `Linux`, `Bluetooth`, `PipeWire`, `Automation`

---

## Technical Skills

<table>
  <tr>
    <td width="33%" valign="top">

### Languages

- C
- C++
- Python
- Bash
- Assembly fundamentals
- Make / CMake basics

    </td>
    <td width="33%" valign="top">

### Embedded

- STM32F4
- ESP32-C3
- STM32 HAL
- FreeRTOS
- Bootloaders
- Interrupts and timers
- UART, SPI, I²C, CAN
- BLE fundamentals
- Low-power firmware

    </td>
    <td width="33%" valign="top">

### Linux / Tools

- Linux kernel modules
- Character drivers
- Virtual network drivers
- Git / GitHub
- GitHub Actions
- GDB
- Logic analyzer debugging
- Doxygen
- Markdown documentation

    </td>
  </tr>
</table>

---

## Engineering Style

I like building projects the way real engineering teams build systems:

1. Start with clear requirements
2. Define the architecture before coding
3. Document important design decisions
4. Build in small, reviewable phases
5. Add validation plans and test strategy
6. Make debugging observable through logs, CLIs, and traces
7. Keep README files useful and honest
8. Treat documentation as part of the engineering output

My goal is to keep improving as an embedded systems engineer while also exploring how AI can make firmware development more structured, traceable, and easier to learn.

---

## What I Am Learning Next

- BLE system design beyond basic examples
- TinyML on embedded sensor nodes
- Advanced Linux driver internals
- Power management and wakeup paths
- OTA and firmware rollback flows
- Production-style embedded test strategy
- AI harnesses for embedded project development
- MCP servers for engineering workflow automation

---

## GitHub Focus

Most of my repositories are built as learning-friendly engineering projects.

I try to include:

- Clear project goals
- Phase-based development plans
- Architecture notes
- Debugging notes
- Validation strategy
- README documentation
- Practical tradeoffs and limitations

I believe a good embedded project should show both the final implementation and the engineering reasoning behind it.

---

## Connect

<p>
  <a href="https://github.com/karangandhi-projects">GitHub</a> ·
  <a href="https://www.linkedin.com/in/karangandhi0210/">LinkedIn</a>
</p>

If any of my projects help you learn embedded systems, Linux drivers, firmware architecture, BLE, or AI-assisted engineering workflows, feel free to open an issue, suggest improvements, or star a repository.
