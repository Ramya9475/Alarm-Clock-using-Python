# Alarm-Clock-using-Python
This repository contains a simple alarm clock application built using Python's Tkinter for the GUI, Pygame for playing sound, and PIL for image handling. The alarm clock allows users to set a specific time and plays an alarm sound when the time is reached.

## Features
Set alarm time with hour, minute, and second precision.
Choose between AM and PM.
Activate or deactivate the alarm.
Plays a sound when the alarm goes off.

## Requirements
Python 3.x
Required Python libraries:
  tkinter
  pygame
  PIL (Pillow)
  datetime

## Code Overview
GUI Setup: The Tkinter library is used to create the graphical user interface. The interface consists of combo boxes for setting the alarm time and radio buttons to activate/deactivate the alarm.

Alarm Functionality: The alarm function runs in a separate thread, continuously checking the current time against the set alarm time. When the times match, the alarm sound is played using the Pygame mixer.

Image Handling: PIL (Pillow) is used to handle the display of images in the application.
