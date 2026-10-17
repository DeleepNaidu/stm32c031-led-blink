# STM32C031 LD4 LED Blink

My first STM32 embedded project using the NUCLEO-C031C6 board and STM32 HAL.

## What it does

Blinks the onboard LD4 LED, connected to PA5.

## How it works

The program sets PA5 high, waits 500 ms, sets it low, then waits another 500 ms in a loop.

## Tools

- STM32CubeIDE
- STM32 HAL
- Wokwi simulator

## What I learned

- How to configure PA5 as a GPIO output
- How to control a GPIO pin with `HAL_GPIO_WritePin`
- How to add delays with `HAL_Delay`
