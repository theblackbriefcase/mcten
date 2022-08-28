# mcten
Arduino Prototype

Arduino Nano
QTY 1 LED BarGraph
QTY 1 LED Yellow
QTY 2 DIP SWITCH 


QTY X Resistors / Type


========== SCOPE  ======

Machine has three user inputs, left button, right button or both buttons together.
on boot, load splash screen, wait for both buttons to be pressed.
If both buttons are pressed, set unlock state = true, set counter state = true
If counterState = true, start counter, if both buttons pressed again, set counterState = false and pause counter
While paused, if left button pressed, decrement counter by one.
while paused, if right button pressed, increment counter by one.
If both buttons pressed while stopped, set counterState = true and continue counter.

loop
