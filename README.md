<!-- Profile README for karangandhi-projects -->

<h1 align="center">Hi, I'm Karan 👋</h1>

<p align="center">
  Embedded / Firmware Engineer &middot; Linux Drivers · STM32 / FreeRTOS · CAN · SPI / I2C · Bootloaders
</p>



## 👨‍💻 What I like building

I enjoy working **close to the hardware–software boundary**:

- Linux kernel modules and virtual drivers
- Bare-metal and RTOS firmware on STM32 (HAL + FreeRTOS)
- Communication stacks (CAN, UART, SPI, I²C)
- Bootloaders, memory maps, and firmware startup flows
- Debug tooling, logging frameworks, and CLIs that make embedded systems observable

Most of my repositories are structured as **learning-friendly, phase-based projects** with clean documentation, so others can follow the evolution of the system—not just the final code.



## 🚀 Highlighted projects

### 🔧 [vnet-driver](https://github.com/karangandhi-projects/vnet-driver)
A step-by-step **Linux virtual Ethernet driver (`vnet0`)** with TX/RX rings, NAPI polling, ethtool support, statistics, and a clear multi-phase roadmap. Designed to mirror how real NIC drivers are structured and debugged.

**Tech:** C, Linux kernel, `net_device`, NAPI, ethtool, CI



### 📡 [stm32-smart-sensor-hub](https://github.com/karangandhi-projects/stm32-smart-sensor-hub)
A **modular, low-power sensor hub** on STM32F446RE that demonstrates real-world **protocol usage and driver abstraction**.

- Cooperative scheduler with task manager
- Power-mode–aware sensor sampling
- UART CLI + live logging dashboard
- Sensor abstraction layer with **real I²C and SPI backends**
  - TSL2591 (I²C light sensor)
  - BME280 (SPI environmental sensor)
- Clean architecture, flow diagrams, and phase-based docs

This project was built specifically to demonstrate **SPI/I²C driver design, integration, and testing** in a production-style firmware layout.

**Tech:** Embedded C, STM32 HAL, SPI, I²C, UART, low-power design, firmware architecture



### 🚗 [mini-ecu-v2](https://github.com/karangandhi-projects/mini-ecu-v2)
A **virtual automotive ECU** on STM32F446RE using FreeRTOS, CAN loopback telemetry, UART CLI + live dashboard, and a **custom bootloader**. Designed as a base for OTA and firmware update experiments.

**Tech:** C, STM32 HAL, FreeRTOS, CAN, UART, bootloader design, CI



### 🧰 [stm32-virtual-vehicle-ecu](https://github.com/karangandhi-projects/stm32-virtual-vehicle-ecu)
A modular STM32F4 ECU-style firmware with FreeRTOS, CAN, UART CLI, and a simple physics-based vehicle model. Focuses on clean separation of drivers, tasks, and application logic.

**Tech:** C, STM32F4, FreeRTOS, CAN, embedded architecture



### 🔁 [embedded-comeback-playground](https://github.com/karangandhi-projects/embedded-comeback-playground)
An STM32 NUCLEO-F446RE **practice sandbox** featuring interrupt-driven UART, CLI tooling, multithreading, and virtual sensors. Used to prototype and validate ideas before moving them into larger projects.

**Tech:** C, STM32, FreeRTOS, drivers, UART/CLI



### 📦 [Pseudo-Character-Device-Driver](https://github.com/karangandhi-projects/Pseudo-Character-Device-Driver)
A basic **pseudo character device driver** implementing open/close/read/write/lseek for multiple devices—useful for understanding Linux file operations and driver lifecycles.

**Tech:** C, Linux kernel, character drivers



## 🛠️ Tech stack & tools

**Languages**
- C (embedded & kernel), C++
- Python (tooling, analysis scripts)
- Bash / Make

**Embedded / Firmware**
- STM32 (F4 series), NUCLEO boards
- STM32 HAL, FreeRTOS
- Bootloaders, linker scripts, memory maps
- **CAN, UART, SPI, I²C**, GPIO, timers, interrupts
- Low-power design and power-mode management

**Linux / Drivers**
- Linux kernel modules (network + character drivers)
- NAPI, TX/RX rings, ethtool
- Driver bring-up, testing, and debugging

**Tooling & Workflow**
- STM32CubeIDE, arm-none-eabi-gcc
- GitHub Actions CI
- Doxygen, Markdown docs
- Git, PR-based workflows



## 📚 What I’m exploring next

- Deeper **power-state integration** (STOP/SLEEP entry & wakeup paths)
- Firmware update flows (UART/CAN flashing, image headers, rollback)
- More advanced **driver observability** (CLI-driven introspection)
- Scaling sensor/driver abstractions toward production-grade layouts



## 🤝 Connect

- 💼 LinkedIn: https://www.linkedin.com/in/karangandhi0210/
- ✉️ Best way to reach me: LinkedIn or GitHub issues on these repos

If any of these projects help you learn embedded systems or Linux driver development, feel free to open an issue, suggest improvements, or ⭐ a repo.
