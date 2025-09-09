Project: clock-display
Authors: David Barnes and Michael Kölling

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling

It is discussed in chapter 3.

To use this project, create an instance of class ClockDisplay. Then inspect this 
instance and leave the object inspector window open. With the inspector window open, 
call the object's methods, such as timeTick and setTime. Watch the 
"displayString" in the inspector.

The displayString field simulates the actual clock display device. Were this 
program running in a real clock, it would change the real, physical display 
hardware instead of this string. The timeTick method would be triggered once 
every minute by some timer hardware.

Everything else could be pretty much the same.


Note: This project does not implement adequate handling of errors.

21. It starts at 00:00 because the default value of the NumberDisplays is 0
23. you would need to call it 60 times. you could also just use the setTime method
24. NumberDisplay digit = new NumberDisplay(10);
25. Rectangle window = new Rectangle(10,20);
26. The second constructor still sets the default hour and minute limits but also starts the 
clock at a custom time using setTime with the values the user passed through the parameters.
27. because it calls setTime which calls updateDisplay, theres no need to do it twice
28. p1.print("essay.txt",True);,p1.getStatus(30)
