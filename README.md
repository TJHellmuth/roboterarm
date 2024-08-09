# roboterarm
Software that can be used with the AR4-MK3 rotbotarm (see: anninrobotics.com)

# Software for the Microcontroller
The Teensky uC is controlling the motor driver. 
It is reading the encoders as well as generating approptiate motor commands.
If  
Note: The absolute value of the encoder is set back to 0 on each uC reset. 

This code is located in the folder embd/ 
# Controlsoftware for the Computer that utilizes the robotarm
There is a graphical unser interface (gui) that can be used to control the robotarm from a computer connected via UART or Ethernet.

This code is located in gui/
# Development code that can be used for debugging

This code is located in dev/
