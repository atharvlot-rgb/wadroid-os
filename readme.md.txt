# WaDroid OS

**WaDroid OS** is a lightweight phone operating system project by **Wacat**.

The goal of WaDroid is to create a fast, simple, modern mobile operating system that can work efficiently on low-end hardware.

## Vision

WaDroid focuses on:

* **Fast** — quick and responsive
* **Lightweight** — designed for limited hardware
* **Simple** — easy to use
* **Wacat** — built around the Wa ecosystem

## Main Components

### WaKernel

WaKernel is the low-level kernel for WaDroid.

Current starter features:

* ARM64/AArch64 entry point
* Kernel stack
* Basic C kernel
* UART output
* Linker script
* Build system

### WaDroid UI

Planned system apps include:

* Home
* Phone
* Messages
* Camera
* Gallery
* Settings
* Browser
* Calculator
* Clock
* WFiles
* WMaps
* WMail
* Wacat AI

## Architecture

```text
WaDroid OS
│
├── WaDroid UI
│   ├── System Apps
│   └── WaApps
│
├── System Services
│
├── WaKernel
│   ├── Memory Management
│   ├── Process Scheduler
│   ├── Interrupts
│   ├── Drivers
│   ├── Filesystem
│   └── Networking
│
└── ARM64 Hardware
```

## Roadmap

### WaKernel 0.1

* ARM64 boot
* Stack setup
* Basic kernel
* UART output

### WaKernel 0.2

* Exception handling
* Interrupts
* Timers
* Physical memory management

### WaKernel 0.3

* Virtual memory
* Page allocator
* Kernel heap

### WaKernel 0.4

* Processes
* Tasks
* Scheduler
* System calls

### WaKernel 0.5

* Display support
* Touchscreen input
* Storage drivers

### WaKernel 0.6+

* Filesystem
* Networking
* Power management
* Security
* Graphical WaDroid interface

## Development

The current kernel is intended for development and emulator testing.

Recommended tools:

* AArch64 cross compiler
* GNU binutils
* Make
* QEMU

## Important

WaDroid is currently a **development project**, not a finished phone operating system.

Do not flash the current WaKernel directly onto a physical phone. Real phones require device-specific bootloader support, drivers, hardware initialization, power management, and other low-level components.

## Project Information

**Name:** WaDroid OS
**Kernel:** WaKernel
**Version:** 0.1
**Project family:** Wacat / WaApps

**Made by Wacat.**
