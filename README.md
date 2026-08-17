# Yang Yifan / finnyoun9

**Embedded Software Engineer** · STM32 · FreeRTOS · ESP32 · ROS 2

Targeting embedded firmware and robotics-control roles in Shenzhen. Background
in TSE for robot-vacuum and smart-home products, with a focus on turning
hardware integration and debugging into reliable firmware evidence.

## Focus

- MCU firmware: C, STM32 HAL, FreeRTOS, Bootloader, OTA, UART/I²C/SPI, watchdogs
- Smart hardware: ESP32 Wi-Fi/Bluetooth gateway, sensors, actuators, local Web control
- Robotics: STM32 real-time control, encoders/PID, Raspberry Pi 5, ROS 2 and `ros2_control`
- Engineering practice: Git, CI, host tests/SIL, logic analyser and oscilloscope-based debugging

## Selected work

| Project | What it proves | Status |
| --- | --- | --- |
| [STM32 Smart-Home OTA System](https://github.com/finnyoun9/stm32-smart-home-ota) | Custom Bootloader, FreeRTOS, ESP32 gateway, wireless OTA and sensor/actuator integration | Hardware-verified core path |
| [Mecanum Mobile Robot](https://github.com/finnyoun9/mecanum-robot) | Shared STM32/Pi protocol, kinematics, ROS 2 integration and firmware SIL | Software-verified; hardware integration in progress |
| [Embedded Debug Toolchain](https://github.com/finnyoun9/embedded-debug-toolchain) | Repeatable hardware-debug workflow using ST-Link, logic analyser and oscilloscope | Active reference |
| [Agent Collab Hub](https://github.com/finnyoun9/agent-collab-hub) | GitHub-based handoffs and multi-agent coding workflow across devices | Active side project |

## Evidence first

Project READMEs separate **hardware-verified results** from simulations, designs
and in-progress work. The current robotics milestone is a single encoder-motor
speed-control demo before expanding to a four-wheel chassis, navigation or a
manipulator.

## Currently building

1. Finish the smart-home project as a stable, documented `v1.0` demo.
2. Assemble and validate the mecanum robot from one motor to four-wheel closed-loop control.
3. Use [agent-collab-hub](https://github.com/finnyoun9/agent-collab-hub/blob/main/docs/macos-agent-workflow.md) to make Codex, VS Code agents and GitHub handoffs reproducible.
