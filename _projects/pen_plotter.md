---
layout: project
title: "Pen Plotter"
main_image: /assets/images/PenPlotterSetup.jpeg
tools: "Python, Numpy"
duration: "1 week"
categories: [Machine Learning, Projects]
tags: [machine learning]
---

## Introduction

I was getting into 3D printer research, and wanted to learn how electronics and programming works together. I decided to create a project which draws 2d images onto paper using a pen. I designed the physical parts in a modelling software (SolidWorks) and sourced the electronics I used online. 

## 3D Printing the parts

I 3D printed the parts for the pen plotter which I designed in solidworks using a Lulzbot Workhorse. To prepare the prints I used a program called prusa slicer which generates the command sequence (called gcode) which tells the printer what to do. 

## Programming the pen plotter

I created a program using python which runs off of a raspberry pi to control the motors. The program takes in a set of commands to run and will pass the control sequences to the stepper motor controllers. 

[Link To Some Sample Control Code](https://github.com/Ashto25/2D_motor_assembly/blob/main/MotorMove.py)

![Plotter Electronics](/assets/images/penPlotterElectronics.jpeg)


## Conclusion

I learned alot from this project and it greatly helped me with learning about how 3D printers and stepper motors work. 