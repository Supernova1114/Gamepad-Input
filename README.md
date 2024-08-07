# Gamepad Input API
A wrapper for Pygame's joystick module
<br>
Author: Cameron Rosenthal @Supernova1114
<br>

Pygame: https://github.com/pygame/pygame

Tested with Python 3.10, Pygame 2.1.2, on Ubuntu 22.04 Desktop & Server
<br>
Tested on Jetson Linux DP 6.0 with Nvidia Jetson AGX Orin.
<br>
Controllers tested: XBox One S, PS4, PS5
<br>
Note: To use on python versions lower than 3.10, switch the match-case statements to if-else branches.

#### Linux install Pygame: 

    pip3 install pygame

#### Features
- Controller hot-plug support.
- Support for matching button and axis layouts across different controllers.
- Function callbacks for button presses (Async), in addition to button value reading.
- Easy access to grouped joystick axis data. (Ex: (x,y) for Left Stick).
- Axis deadzones.
- Muliple-controller support.
#### Examples and Gamepad tester
- Example use of API is shown in api_example.py
- Pygame's gamepad tester is controller_test.py
#### Creating a controller configuration
- Use controller_test.py or an online gamepad tester to see button and axis ID's, and controller name.
- Open gamepads.config and assign correct ID's to each button / axis.
- Make sure controller name is correct.

![](repo-images/gamepad-input.gif)
