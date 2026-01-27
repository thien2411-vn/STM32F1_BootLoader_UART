# STM32F1 BootLoader UART

This repository hosts the firmware for a lightweight and efficient UART-based bootloader designed specifically for STM32F1 microcontrollers. With an aim to simplify firmware updates and streamline the development process, this project showcases expertise in embedded C programming, with a primary focus on reliability and performance.

---

## Features

- **Lightweight and Configurable Bootloader**:
  - Streamlined design with minimal memory overhead.
  - Easily adaptable for various STM32F1 configurations.

- **UART Communication**:
  - Reliable, bi-directional communication protocol.
  - Supports a wide range of baud rates for flexible integration.

- **Robust Error Handling**:
  - Detects transmission errors.
  - Ensures data integrity during updates or communication exchanges.

---

## Requirements

- **Hardware**:
  - STM32F1 microcontroller with appropriate UART pins.

- **Software and Tools**:
  - STM32CubeIDE or other ARM-based IDEs with C support.
  - UART terminal software such as TeraTerm, Putty, or equivalent.

- **Knowledge Base**:
  - Familiarity with STM32F1 registers and UART communication.
  - An understanding of low-level bootloaders and their MCU interactions.

---

## Setup and Usage

### 1. Building the Bootloader
- Clone the repository:
  ```bash
  git clone https://github.com/thien2411-vn/STM32F1_BootLoader_UART.git
  ```
- Open the project in your preferred IDE (e.g., STM32CubeIDE).

- Compile the project with the desired configuration:
  - Ensure all UART parameters match your hardware setup.

### 2. Flashing
- Connect your STM32F1 microcontroller to your PC.
- Use a bootloader-compatible flashing tool (like STM32CubeProgrammer).
- Follow the instructions to upload the compiled binary (`.bin` or `.hex`) file.

### 3. Communication via UART
- Connect your UART terminals to the designated TX/RX pins on STM32F1.
- Ensure the baud rate matches your firmware configuration.
- Transmit and receive data as required.

---

## Contribution

Feel free to fork this repository and propose new features or fixes via pull requests. Contributions to improving the bootloader's robustness or adding new interfaces (e.g., SPI) are highly welcomed.

---

## Acknowledgements

Special thanks to the open-source communities for offering tools, examples, and documentation that made this development a success!

---

## Languages Used

- **C**: 99.3%
- **Other**: 0.7%
