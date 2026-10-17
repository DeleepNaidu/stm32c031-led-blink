# STM32C031 LD4 LED Blink

My first STM32 embedded project using the NUCLEO-C031C6 and STM32 HAL.

## What it does
Blinks the onboard LD4 LED connected to PA5: on for 500 ms, then off for 500 ms.

## Source files
- `Core/Src/main.c` — program entry point and blink loop
- `Core/Inc/main.h` — shared declarations and pin definitions

## Tools
- STM32CubeIDE
- STM32 HAL
- Wokwi simulator

## What I learned
- Configure PA5 as a GPIO output
- Set a GPIO pin with `HAL_GPIO_WritePin`
- Add timing with `HAL_Delay`
