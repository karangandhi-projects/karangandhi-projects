<!-- Profile README for karangandhi-projects -->

<h1 align="center">Hi, I'm Karan 👋</h1>

<p align="center">
  Embedded / Firmware Engineer &middot; Linux Drivers · STM32 / FreeRTOS · CAN / Bootloaders
</p>



## 👨‍💻 What I like building

I enjoy working close to the metal:

- Linux kernel modules and virtual drivers
- Bare-metal / RTOS firmware on STM32 (FreeRTOS + HAL)
- Bootloaders, memory maps, and firmware update flows
- Debug tooling, logging frameworks, and CI that keeps embedded projects honest

Most of my repos are structured as **learning-friendly, step-by-step projects**, so someone else can follow along and learn from the code.



## 🚀 Highlighted projects

### 🔧 [vnet-driver](https://github.com/karangandhi-projects/vnet-driver)
A step-by-step **Linux virtual Ethernet driver (`vnet0`)** with TX/RX rings, NAPI, ethtool, stats, and a clear roadmap of phases. Includes dynamic debug usage, CI, and plans for a userspace backend. :contentReference[oaicite:3]{index=3}  

**Tech:** C, Linux kernel, net_device, NAPI, ethtool



### 🚗 [mini-ecu-v2](https://github.com/karangandhi-projects/mini-ecu-v2)
A **virtual automotive ECU** on STM32F446RE with FreeRTOS, CAN loopback telemetry, a UART CLI + live dashboard, logging framework, and a **custom bootloader** (Phase 1 & 2 complete). Includes CI builds with ARM-GCC and detailed docs/roadmap. :contentReference[oaicite:4]{index=4}  

**Tech:** C, STM32 HAL, FreeRTOS, CAN, UART, bootloader design, CI



### 🧰 [stm32-virtual-vehicle-ecu](https://github.com/karangandhi-projects/stm32-virtual-vehicle-ecu)
A modular **STM32F4 virtual vehicle ECU** with FreeRTOS, CAN, UART CLI, and a physics-based vehicle model – a more “from-scratch” version of the ECU idea with focus on clean architecture and modularization. :contentReference[oaicite:5]{index=5}  

**Tech:** C, STM32F4, FreeRTOS, CAN, embedded architecture



### 🔁 [embedded-comeback-playground](https://github.com/karangandhi-projects/embedded-comeback-playground)
An STM32 NUCLEO-F446RE **practice playground** with interrupt-driven UART, CLI, multithreading, and a modular virtual sensor architecture using STM32CubeIDE + FreeRTOS. A “sandbox” to get back into embedded development. :contentReference[oaicite:6]{index=6}  

**Tech:** C, STM32, FreeRTOS, drivers, UART/CLI



### 📦 [Pseudo-Character-Device-Driver](https://github.com/karangandhi-projects/Pseudo-Character-Device-Driver)
A basic **pseudo character device driver** that mimics a real char driver with open/close/read/write/lseek operations and multiple devices. Great for understanding file operations in the Linux kernel. :contentReference[oaicite:7]{index=7}  

**Tech:** C, Linux kernel, char drivers



### ⏱️ [EE-6314-RTOS](https://github.com/karangandhi-projects/EE-6314-RTOS)
A multi-threaded **RTOS design for TM4C123GH6PM** implementing pre-emptive and co-operative scheduling, semaphores, and core kernel APIs (yield/sleep/wait/signal). University project that kick-started my RTOS interest. :contentReference[oaicite:8]{index=8}  

**Tech:** C, RTOS design, ARM Cortex-M4F



## 🛠️ Tech stack & tools

**Languages**

- C (embedded & kernel), C++
- Python (tooling, scripts)
- Bash / Make

**Embedded / Firmware**

- STM32 (F4 series), NUCLEO boards
- STM32 HAL, FreeRTOS
- Bootloaders, linker scripts, memory maps
- CAN, UART, GPIO, timers, interrupts

**Linux / Drivers**

- Linux kernel modules (net_device, char drivers)
- NAPI, TX/RX rings, ethtool
- Netlink/ioctl (planned for vnet-driver)

**Tooling & Workflow**

- STM32CubeIDE, arm-none-eabi-gcc
- GitHub Actions CI
- Doxygen, markdown docs
- Git, GitHub pull-request workflows



## 📚 What I’m exploring / improving

- More advanced **network driver features** (better packet handling, more ethtool ops)
- **Firmware update flows** (UART/CAN flashing, secure updates, image headers, rollback)
- Polished **CLI tools / GUIs** to interact with embedded targets
- Cleaner, more reusable driver/RTOS abstractions



## 🤝 Connect

- 💼 LinkedIn: https://www.linkedin.com/in/karangandhi0210/
- ✉️ Best way to reach me: via LinkedIn or GitHub issues on these repos

If any of these projects help you learn embedded or Linux driver development, feel free to open an issue, suggest improvements, or just ⭐ the repo.
