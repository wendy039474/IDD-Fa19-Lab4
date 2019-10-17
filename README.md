# Paper Puppets

*A lab report by Wen-Ying(Rei) Lee

## Part A. Actuating DC motors

[Rei_Vibration Motor](//youtu.be/xZpsS7Zt-Mo)

## Part B. Actuating Servo motors

### Part 1. Connect the Servo to your breadboard

**a. Which color wires correspond to power, ground and signal?**

Black: Gound; Red: Power; Orange: Singal.

### Part 2. Connect the Servo to your Arduino

**a. Which Arduino pin should the signal line of the servo be attached to?**

Based on the Sweep example code ("myservo.attach(9);"), the signal line of the servo motor should be connected to Arduino Pin 9.

**b. What aspects of the Servo code control angle or speed?**

For angle, the code uses the command "myservo.write(pos);" to set the servo motor to "pos" degree position, and this is based on the pulse width of the servo. For the speed of the movement, the code uses for loop to increase the position degree, by changing the delat amount within the for loop, you can change the speed of the servo movement.

## Part C. Integrating input and output

**Include a photo/movie of your raw circuit in action.**

[Rei_ServoSwitch](//youtu.be/FLDiWHbwbA4)

A servo motor that will turn off your switch whenever you turn on the switch!

## Part D. Paper puppet

**a. Make a video of your proto puppet.**

[Rei_Paper Puppet](//youtu.be/bUrvEbyP7as)

## Part E. Make it your own

**a. Make a video of your final design.**
 
