# STM32 SD Card System with UART Ring Buffer

This project implements an STM32-based system that interacts with an SD card using UART communication and a ring buffer. The code is still in early development and may undergo changes.

## Project Overview

- **Controller:** STM32 (STM32F407VET6)
- **debugger** ST-LINK/V2
- **Development Environment:** STM32CubeIDE
![7923300-1](https://github.com/hoosmalhoos/stm32-SdCardSystem/assets/38074334/5c115e4e-a712-44d1-b685-53bbd0e84adf)

## Features

- SD card communication via UART
- Ring buffer implementation for data handling

## Getting Started

### Prerequisites

- STM32CubeIDE installed
- Appropriate STM32 hardware or development board (STM32F4xx series or any SDIO featured)

### Setting up the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/hoosmalhoos/stm32-SdCardSystem/tree/main

compile code:
- make sure to import the project
- power STM32 development board via USB and hook it up to STM32 Debugger ST-LINK/V2 throw SWD  mode Connection
- Recommended Stm32F4xx Series which has SDIO featured
- run debug mode


.

