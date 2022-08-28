# mcten
Arduino Prototype<br/>
<br/>
Arduino Nano<br/>
QTY 1 LED BarGraph<br/>
QTY 1 LED Yellow<br/>
QTY 2 DIP SWITCH <br/>
<br/>
<br/>
QTY X Resistors / Type<br/>
<br/>
<br/>
========== SCOPE  ======<br/>
<br/>
Machine has three user inputs, left button, right button or both buttons together.<br/>
on boot, load splash screen, wait for both buttons to be pressed.<br/>
If both buttons are pressed, set unlock state = true, set counter state = true<br/>
If counterState = true, start counter, if both buttons pressed again, set counterState = false and pause counter<br/>
While paused, if left button pressed, decrement counter by one.<br/>
while paused, if right button pressed, increment counter by one.<br/>
If both buttons pressed while stopped, set counterState = true and continue counter.<br/>
<br/>
loop<br/>
