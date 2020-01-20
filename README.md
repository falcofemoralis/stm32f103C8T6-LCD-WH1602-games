# stm32f103C8T6-LCD-WH1602-games

You have to add HD44780 library to your project and setting it up in hd44780_driver.h

In my project I used PB7 for button 1 and PB8 for button 2

Also I used coocox coIDE 1.7.8 (for some reason in previous version rand function didn't work)

plus you have to add libs in repository

#include "stm32f10x_rcc.h"
#include "stm32f10x_rtc.h"
#include "stm32f10x_tim.h"
#include "stm32f10x_pwr.h"
#include "stm32f10x_gpio.h"

You can choose, should you use LEDS or not
#define useLED 1

yellow PB0/
green PB1/
red PB5/
blue PB6

button1 = PB7 / button2 = PB8

1) hangmanduino

how to play:

move selector with button1(right) and button2(left)

choose letter with long press button1
