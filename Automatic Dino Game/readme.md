# Automatic Dino Game

## ORIGINAL PROJECT

The Chrome dino game is played by a bot on its own.An LDR sensor senses if the black colour is of enough percentage on the monitor and signals the arduino, which communicates with python via pyserial and presses the space button using pyautogui. This lets the game play on its own.

### Materials -
Arduino Nano, LDR sensor , 10 k ohm resistor, python

### Input
The LDR sensor senses if light is not present( if enough black colour of the obstacle  is displayed on the screen) and sends input to the arduino.

### Microcontroller
The arduino is used as the microcontroller here, which takes in input from the LDR sensor and sends output signal as high if the value is below a certain number( which can be procured via experiments)

### Output
Python recieves the signals given by the arduino via pyserial and if the value is high it presses space bar at appropriate times using pyautogui.

## BETTER SOLUTION

### Input 
A Phototransistor can be used instead of photoresistor(LDR), which has higer sensitivity to light, lesser reaction time and cheaper, but physically placing it on the screen may be difficult as it takes light from one direction.

### Microcontroller
Another microcontroller can be used fro it to be cost effective but Arduino is just fine.

### Output
A servo motor can be fixed to press the space bar instead of using python which may seem easy to understand for beginners, but the python code is really simple and can be learnt easily, and doesnt take any physical strain/problems so better if we use python to execute the project. 

## A different approach
An AI can be built based on reinforcement learning using Q-Learning. This will not have any physical objects like LDR and hence more efficient, but it may be difficult for beginers to grasp.But if learnt it would teach a lot of stuff, and lesser power consumption except that it may take up more memory, and its cost effective too.
