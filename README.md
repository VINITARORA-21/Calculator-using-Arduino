# Calculator-using-Arduino
This project implements a basic calculator using Arduino, a 4x4 keypad, and a 16x2 LCD display. The calculator performs addition, subtraction, multiplication, and division operations on two numbers entered via the keypad.

# Components Used

* Arduino board                                                                                                           
* 4x4 keypad
* 16x2 LCD display
* Potentiometer (for adjusting LCD contrast)
* Jumper wires

# Libraries Required

* LiquidCrystal_I2C: Library for controlling LCD displays via I2C communication.
* Keypad: Library for interfacing with matrix-style keypads.
* link: https://www.arduino.cc/reference/en/libraries/

# Installation

* Connect the keypad rows to Arduino pins 0, 1, 2, and 3.
* Connect the keypad columns to Arduino pins 4, 5, 6, and 7.
* Connect the LCD display's SDA pin to Arduino's A4 pin, and SCL pin to A5.
* Connect the LCD display's VCC and GND pins to Arduino's 5V and GND pins, respectively.
* Adjust the contrast of the LCD using the potentiometer.
* Upload the provided Arduino sketch (calculator.ino) to your Arduino board.
* Power up your Arduino board and start using the DIY calculator!

# Usage

* Press the keys on the keypad to input numbers and perform calculations.
* Use the '*' key to clear the current calculation.
* Press the '#' key to execute the entered operation and display the result.
* After a result is displayed, you can start a new calculation by entering numbers and an operator.
