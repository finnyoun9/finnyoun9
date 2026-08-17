<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=soft&color=0:0f172a,100:334155&height=150&section=header&text=Yang%20Yifan%20/%20finnyoun9&fontSize=36&fontColor=e2e8f0&desc=Embedded%20Software%20Engineer%20%C2%B7%20STM32%20%C2%B7%20FreeRTOS%20%C2%B7%20ROS%202&descSize=16&descAlignY=68&fontAlignY=38">
  <img src="https://capsule-render.vercel.app/api?type=soft&color=0:0f172a,100:334155&height=150&section=header&text=Yang%20Yifan%20/%20finnyoun9&fontSize=36&fontColor=e2e8f0&desc=Embedded%20Software%20Engineer%20%C2%B7%20STM32%20%C2%B7%20FreeRTOS%20%C2%B7%20ROS%202&descSize=16&descAlignY=68&fontAlignY=38" width="100%">
</picture>

![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-000000?style=flat-square)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![ROS 2](https://img.shields.io/badge/ROS_2-22314E?style=flat-square&logo=ros&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi_5-C51A4A?style=flat-square&logo=raspberrypi&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</div>

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
| [STM32 Smart-Home OTA System](https://github.com/finnyoun9/stm32-smart-home-ota) | Custom Bootloader, FreeRTOS, ESP32 gateway, wireless OTA and sensor/actuator integration | ![hardware-verified](https://img.shields.io/badge/hardware--verified-2ea44f?style=flat-square) |
| [Mecanum Mobile Robot](https://github.com/finnyoun9/mecanum-robot) | Shared STM32/Pi protocol, kinematics, ROS 2 integration and firmware SIL | ![software-verified](https://img.shields.io/badge/software--verified-dbab09?style=flat-square) |
| [Embedded Debug Toolchain](https://github.com/finnyoun9/embedded-debug-toolchain) | Repeatable hardware-debug workflow using ST-Link, logic analyser and oscilloscope | ![active](https://img.shields.io/badge/active--reference-0969da?style=flat-square) |
| [Agent Collab Hub](https://github.com/finnyoun9/agent-collab-hub) | GitHub-based handoffs and multi-agent coding workflow across devices | ![active](https://img.shields.io/badge/active--side--project-8250df?style=flat-square) |

## Evidence first

Project READMEs separate **hardware-verified results** from simulations, designs
and in-progress work. The current robotics milestone is a single encoder-motor
speed-control demo before expanding to a four-wheel chassis, navigation or a
manipulator.

## Currently building

1. Finish the smart-home project as a stable, documented `v1.0` demo.
2. Assemble and validate the mecanum robot from one motor to four-wheel closed-loop control.
3. Use [agent-collab-hub](https://github.com/finnyoun9/agent-collab-hub/blob/main/docs/macos-agent-workflow.md) to make Codex, VS Code agents and GitHub handoffs reproducible.

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=finnyoun9&show_icons=true&theme=dark&hide_border=true&bg_color=00000000&title_color=e2e8f0&text_color=94a3b8&icon_color=64748b">
  <img src="https://github-readme-stats.vercel.app/api?username=finnyoun9&show_icons=true&theme=default&hide_border=true&bg_color=ffffff00" width="49%">
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=finnyoun9&layout=compact&hide_border=true&bg_color=00000000&title_color=e2e8f0&text_color=94a3b8">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=finnyoun9&layout=compact&hide_border=true&bg_color=ffffff00" width="35%">
</picture>

</div>
