# STM32F103RCT6 Core Board V1

## Design Goal

Design a reusable STM32F103RCT6 core board for SmartCar V1
and future embedded projects.

## MCU

STM32F103RCT6
- Cortex-M3
- 72 MHz
- 256 KB Flash
- 48 KB SRAM
- LQFP64

## Core Modules

- 5V input
- On-board 3.3V regulator
- VDD/VSS decoupling
- VDDA/VSSA filtering
- 8 MHz HSE
- Optional 32.768 kHz LSE footprint
- NRST button
- BOOT0 configuration
- SWD interface
- Debug UART
- User LED
- GPIO headers

## Verification Plan

1. Check 3.3V power rail
2. Connect ST-Link through SWD
3. Read MCU device successfully
4. Download LED Blink
5. Verify Debug UART
6. Verify HSE / 72 MHz system clock
7. Test GPIO and PWM