# Batmobile

## Overview
“Batmobile” project was developed as a part of the Computer Graphics course at Faculty of Technical Sciences in Novi Sad. This GitHub repository contains the source code for the Batmobile 2D and 3D project, implemented using OpenGL. The full 2D specification is available [**here**](https://github.com/MilenaM06/Batmobile-Computer-Graphics/blob/main/BATMOBILE_2D/Specification/Batmobile_2D_Specification_English.pdf), the full 3D specification is available [**here**](https://github.com/MilenaM06/Batmobile-Computer-Graphics/blob/main/BATMOBILE_3D/Specification/Batmobile_3D_Specification_English.pdf) and the project demo can be downloaded [**here**](https://github.com/MilenaM06/Computer-Graphics/blob/main/BATMOBILE_3D/batmobile_3D_demo.mkv).

## Final Look
![Final look](https://github.com/MilenaM06/Computer-Graphics/blob/main/BATMOBILE_3D/batmobile_3D_gif.gif)

## Features

### 2D Dashboard:
- **Tachometer**: Displays engine RPM with a color-changing needle.
- **Kilometer Progress Bar**: Indicates distance traveled, resetting after 10 km.
- **Warning Indicators**: "Check Engine" and "Battery Problem" lights can be toggled with `C` and `B` keys.
- **Transmission Gear Indicator**: Circular indicator flashes based on current gear.
- **Graphic Display**: Moves a "blind mouse" symbol with WASD keys, which changes based on the car's gear.

### 3D Features:
- **3D Cabin**: Includes dashboard and external scene visible through the windshield.
- **Movement & Controls**: Car can move forward/backward and left/right with automatic transmission. Left-right movement is slower.
- **Street & Buildings**: Car moves along a street with buildings on both sides.
- **Lighting & Night Mode**: Includes Phong lighting model, directional light (mimicking the moon), and headlights with night vision.
- **Interactive Dashboard**: All instruments update based on car behavior, including the tachometer showing current gas level.
- **Steering Wheel**: A 3D model of the steering wheel is included.
