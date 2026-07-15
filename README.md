# Sourya Development Board

<p align="center">
  <img src="docs/images/sourya_logo.png" alt="Sourya Development Board" width="250"/>
</p>

<p align="center">
  <strong>An STM32-Based Development Platform for Embedded Systems, Robotics, and IoT Applications</strong>
</p>

---

## Overview

The **Sourya Development Board** is a versatile embedded development platform designed to simplify learning, prototyping, and product development using STM32 microcontrollers. The board provides easy access to digital I/O, communication interfaces, debugging capabilities, and peripheral integration, making it suitable for:

* Embedded Systems Development
* Robotics Applications
* Internet of Things (IoT)
* Sensor Interfacing
* Motor Control Systems
* Automation Projects
* Educational and Research Purposes

The board is intended to provide a unified hardware platform that enables developers, students, and researchers to rapidly build and test embedded applications.

---

## Key Features

* STM32-based high-performance microcontroller
* Multiple Digital Input/Output Pins
* UART Communication Support
* PWM Generation Support
* ADC and Sensor Interface Capability
* I2C Communication Interface
* SPI Communication Interface
* On-board Debugging Support through ST-LINK
* Expandable GPIO Headers
* Suitable for Real-Time Embedded Applications

---

## Hardware Architecture and Pin Mapping

![alt text] (Refer <PIN MAPPING.jpg>)

The Sourya board is designed around the STM32 ecosystem and supports various peripheral modules and external devices.

### Supported Interfaces

| Interface | Description                         |
| --------- | ----------------------------------- |
| GPIO      | Digital Input and Output            |
| UART      | Serial Communication                |
| PWM       | Motor and Actuator Control          |
| ADC       | Analog Sensor Interfacing           |
| I2C       | Sensor and Peripheral Communication |
| SPI       | High-Speed Peripheral Communication |
| Timers    | Timing and Control Applications     |

---

## Development Environment

The recommended development environment for the Sourya board is:

* **IDE:** STM32CubeIDE
* **Programming Language:** C
* **Framework:** STM32 HAL (Hardware Abstraction Layer)

### Download STM32CubeIDE

Official Download Link:

https://www.st.com/en/development-tools/stm32cubeide.html

---

# Getting Started

## Prerequisites

Before starting development, ensure you have:

* Sourya Development Board
* USB Cable
* Computer running Windows, Linux, or macOS
* STM32CubeIDE Installed

---

# Creating a New Project

## Step 1: Launch STM32CubeIDE

Open STM32CubeIDE and select a workspace.

---

## Step 2: Create a New STM32 Project

1. Click:

```
File → New → STM32 Project
```

2. Select the target STM32 microcontroller used on the Sourya board.

3. Click **Next**.

---

## Step 3: Configure Project Details

Enter:

* Project Name
* Project Location
* Toolchain: STM32CubeIDE

Click **Finish**.

---

## Step 4: Configure Peripherals

Use the **Pinout & Configuration** window to configure:

* GPIO
* UART
* Timers
* PWM
* I2C
* SPI
* ADC

according to your application requirements.

---

## Step 5: Generate the Project

Click:

```
Project → Generate Code
```

STM32CubeIDE will automatically generate the project structure.

---

## Step 6: Build the Project

Click:

```
Project → Build Project
```

or use:

```
Ctrl + B
```

---

## Step 7: Program the Board

1. Connect the Sourya board.
2. Click:

```
Run → Debug
```

or

```
Run → Run
```

STM32CubeIDE will automatically build and flash the firmware onto the board.

---

# Typical Development Workflow

```
Create Project
       ↓
Configure Peripherals
       ↓
Generate Code
       ↓
Write Application Code
       ↓
Build Project
       ↓
Flash to Board
       ↓
Debug and Test
```

---


# Documentation

Project-specific examples and application notes can be found inside the respective directories of this repository.

---

# Contributing

Contributions are welcome.

If you would like to improve the documentation, add examples, or contribute enhancements to the Sourya ecosystem, please create an issue or submit a pull request.

---

# License

This project is released under the MIT License.

---

# Contact

**Sourya Development Board Team**

For updates and documentation, please refer to this repository.

---


