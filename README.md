<div align="center">

# 杨一帆 · Yang Yifan

**Embedded Firmware Engineer · Shenzhen**<br>
STM32 · FreeRTOS · Bootloader / OTA · Robotics Control

![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-000000?style=flat-square)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![ROS 2](https://img.shields.io/badge/ROS_2-22314E?style=flat-square&logo=ros&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/CI-GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

Open to embedded firmware and robotics-control opportunities in Shenzhen.<br>
Contact: [finnyoun9@gmail.com](mailto:finnyoun9@gmail.com)

</div>

## What I build

- **MCU firmware** — C, STM32 HAL, FreeRTOS, bootloaders, OTA, UART / I²C / SPI, watchdogs
- **Robotics control** — motor drivers, encoders, PID/kinematics, STM32↔Raspberry Pi communication, ROS 2 / `ros2_control`
- **Hardware-aware engineering** — board bring-up, logic-analyser and oscilloscope debugging, CI and SIL tests

## Selected evidence

| Project | Evidence | Verification |
| --- | --- | --- |
| [STM32 Smart-Home OTA System](https://github.com/finnyoun9/stm32-smart-home-ota) | STM32F103 + FreeRTOS + ESP32; custom **8 KB Bootloader**, CRC-32, chunk ACK and retry; sensor/actuator integration | **Hardware-verified OTA end-to-end:** PC → Bluetooth SPP → ESP32 → STM32 Bootloader → Flash → application jump |
| [Mecanum Mobile Robot](https://github.com/finnyoun9/mecanum-robot) | TB6612 four-wheel drive, encoder/PID control code, shared STM32/Pi binary protocol, kinematics and ROS 2 integration | Four motors direction-tested on hardware; firmware command/control chain covered by host-side SIL + CI |
| [Embedded Debug Toolchain](https://github.com/finnyoun9/embedded-debug-toolchain) | Repeatable ST-Link, logic-analyser and oscilloscope workflow for firmware debugging | Active reference for board-level bring-up and protocol diagnosis |

> Project READMEs explicitly separate hardware-verified results from simulation, design work and in-progress milestones.

## Background

Previously worked as a TSE on robot-vacuum and smart-home products. I bring product-level integration, issue isolation and test-closure habits to embedded firmware development.

Currently deepening Linux/driver fundamentals alongside MCU and robot-control work.
