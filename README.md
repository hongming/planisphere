## 新功能 What's new in 2025 
增加中文界面支持，可制作中文华星座、盘面 Add Chinese language support 
新增天体模块，通过补充csv文件，以十字形标记这些新天体的RA/DEC坐标 Add other celestial bodies and mark the position with a cross

## Make your own cardboard model planisphere

This repository contains Python scripts that can be used to produce a cardboard cut-and-glue kit to make your own model planisphere.

### Introduction

A planisphere is a simple hand-held device which shows a map of which stars are visible in the night sky at any particular time. By rotating a wheel, it shows how stars move across the sky through the night, and how different constellations are visible at different times of year.

See <https://in-the-sky.org/planisphere/index.php> for more information, including detailed assembly instructions.

### Getting started

To make planisphere models for all latitudes, at five degree intervals, run the shell script `main_planisphere.sh`.

### Caveat

Planispheres do not work well when used close to the equator. The scripts in this repository do not allow you to create planispheres for latitudes between 15&deg;N and 15&deg;S, as the celestial pole is too close to the horizon.

## Author

This code was developed by Dominic Ford <https://dcford.org.uk>. It is distributed under the Gnu General Public License V3.

