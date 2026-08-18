<div align="center">

# 杨一帆 Yang Yifan

**嵌入式软件工程师 · Embedded Software Engineer**
STM32 · FreeRTOS · ESP32 · ROS 2

![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-000000?style=flat-square)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![ROS 2](https://img.shields.io/badge/ROS_2-22314E?style=flat-square&logo=ros&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi_5-C51A4A?style=flat-square&logo=raspberrypi&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</div>

求职方向：深圳，嵌入式固件 / 机器人控制岗位。曾任扫地机器人与智能家居产品测试工程师（TSE），现专注于把硬件集成与调试经验转化为可靠的固件证据。

Targeting embedded firmware and robotics-control roles in Shenzhen. Background
in TSE for robot-vacuum and smart-home products, with a focus on turning
hardware integration and debugging into reliable firmware evidence.

## Focus 技术方向

- MCU firmware（MCU 固件）: C, STM32 HAL, FreeRTOS, Bootloader, OTA, UART/I²C/SPI, watchdogs
- Smart hardware（智能硬件）: ESP32 Wi-Fi/Bluetooth gateway, sensors, actuators, local Web control
- Robotics（机器人控制）: STM32 real-time control, encoders/PID, Raspberry Pi 5, ROS 2 and `ros2_control`
- Engineering practice（工程实践）: Git, CI, host tests/SIL, logic analyser and oscilloscope-based debugging

## Selected work 代表项目

| Project 项目 | What it proves 亮点 | Status 状态 |
| --- | --- | --- |
| [STM32 Smart-Home OTA System](https://github.com/finnyoun9/stm32-smart-home-ota) | Custom Bootloader, FreeRTOS, ESP32 gateway, wireless OTA and sensor/actuator integration | ![hardware-verified](https://img.shields.io/badge/hardware--verified-2ea44f?style=flat-square) |
| [Mecanum Mobile Robot](https://github.com/finnyoun9/mecanum-robot) | Shared STM32/Pi protocol, kinematics, ROS 2 integration and firmware SIL | ![software-verified](https://img.shields.io/badge/software--verified-dbab09?style=flat-square) |
| [Embedded Debug Toolchain](https://github.com/finnyoun9/embedded-debug-toolchain) | Repeatable hardware-debug workflow using ST-Link, logic analyser and oscilloscope | ![active](https://img.shields.io/badge/active--reference-0969da?style=flat-square) |
| [Agent Collab Hub](https://github.com/finnyoun9/agent-collab-hub) | GitHub-based handoffs and multi-agent coding workflow across devices | ![active](https://img.shields.io/badge/active--side--project-8250df?style=flat-square) |

## Evidence first 先看证据

项目 README 严格区分"硬件已验证的结果"与仿真、设计和进行中的工作。当前机器人里程碑是单编码器电机调速闭环，下一步扩展到四轮底盘、导航或机械臂。

Project READMEs separate **hardware-verified results** from simulations, designs
and in-progress work. The current robotics milestone is a single encoder-motor
speed-control demo before expanding to a four-wheel chassis, navigation or a
manipulator.

## Currently building 当前推进

1. Finish the smart-home project as a stable, documented `v1.0` demo.（智能家居项目收口为稳定的 v1.0 demo）
2. Assemble and validate the mecanum robot from one motor to four-wheel closed-loop control.（机器人从单电机调速扩展到四轮闭环验证）
3. Use [agent-collab-hub](https://github.com/finnyoun9/agent-collab-hub/blob/main/docs/macos-agent-workflow.md) to make Codex, VS Code agents and GitHub handoffs reproducible.（用 agent-collab-hub 让多 agent 协作跨设备可复现）
