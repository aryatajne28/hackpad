# Cyao's mega macropad
Hello! This is my submission for hackpad! This was made for Hackpad v1.

## Features
- 4x Neopixels!
- A big 0.96" OLED screen
- Cool silkcreen art
- 16x whole kailh choc keys (they were allowed for v1)
- kmk firmware! Control your mouse with this macropad

## PCB
Here are pictures of my pcb:

| **Schematic** | **PCB** |
|---------------|---------|
|![](https://i.ibb.co/GvsRwfvR/image.png)|![](https://i.ibb.co/fJRxwY7/image.png)|

Hope you like it! I made like 10 revisions. 

![](https://cloud-fwkk14f6r-hack-club-bot.vercel.app/0screenshot_2024-10-09_at_9.59.15_pm.png)

PS. there is a strict assembly order, dm me (`@Cyao` on slack) to know it

[x] I ran DRC and there are 0 errors

## CAD
Designed using FreeCAD! It was painful. Be glad you have the current guide, I spent 10+ hours figuring out how to do everything correctly (and even like this I still did stupid stuff).

![](https://cloud-3jqi500oq-hack-club-bot.vercel.app/2screenshot_2024-10-06_at_3.43.34_pm.png)

Everything fits together with 4 m3 screws and bolts

## Firmware

I wrote the firmware using kmk, you can see it inside the repo. It can be used to control your mouse!

## Notes
Making the pad was fun ^.^ but I was just too paranoid that something would go wrong and made 15+ revisions lol. Ended up learning how to use OpenSCAD and FreeCAD.

## BOM
- 1 SEEEDUINO XIAO RP2040
- 16x [Kailh Choc V2 switches](https://www.kailh.net/products/kailh-choc-v2-low-profile-switch-set)
- 16x 1N4148 diodes
- 1x SSD1306 128x64O LED (5V VCC, 3.3V logic, I2C)
- 4x [SK6812-MINI-E LED](https://www.adafruit.com/product/4960)
- 2x 4.7k resistor
- 4x 0.1 uF capacitor (code 104, not obligatory but best have)
- 1x 1 uF capacitor (105 not obligatory)
- 4x same screws as orpheuspad and corresponding nuts

