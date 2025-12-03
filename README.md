# Film-Camera-Lightmeter
A PCB I designed to integrate a light meter onto my film camera.  
My inspiration for this was when I got my first film camera, a Cannon AE-1, I noticed the built-in light-meter was broken.  
For most of my time, I have been using my phone with a light-meter app to adjust my camera settings but that got annoying quick. 
Since I wanted to practice more PCB design, I figured the best way to get practice in and solve my issue is to make my own light meter and manufacture a PCB for it.

## PCB Features
 - Raspberry Pi Pico MCU
 - VEML7700-TR Ambient Light Sensor
 - Lipo battery charging circuit
 - Button control inputs
 - Automatic switching between USB power & Battery power
 - Static Discharge protection

## PCB Design

The PCB is a 2-layer board to minimize cost.  

It uses a Raspberry Pi Pico MCU as it was a relatively new board I was trying to learn to use. 
To power it, you can supply either USB-C for development, or a 3.7V Lipo battery.

It is still a WIP and I hope to have it manufactured soon.


![ScreenShot](Screenshots/Schematic.png)

![ScreenShot](Screenshots/layout.png)

![ScreenShot](Screenshots/3dview.png)
