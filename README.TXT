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


Note: This project does not implement adequate handling of errors

21. The values of the objects it created are 0.
23. You would need to call the method 60 times or you can call the setTime method and set the minutes to 60.
24. NumberDisplay digit = new NumberDisplay(10);
25. Rectangle window = new Rectangle(12, 10)
26. The second constructor allows you to create a clock display with you own limits for the hours and minutes.
It does this by adding parameters.
27. The second constructor has parameters while the first doesn't. 
The second doesn't have the updateDisplay method 
because it has the setTime display which has the updateDisplay method in it.
28.
p1.print("File", True);
p1.getStatus(1);
29. Triangles, squares, and circles.
30.
roof = new Triangle();
roof.changeSize(60, 180);
roof.moveHorizontal(20);
roof.moveVertical(-60);
roof.makeVisible();
roof.changeColor("black");
roof.changeColor("green");
31. Yes.
32. 2.
33. It accepts negative numbers.
34. Any integer ranging from -4 to 4.
35. Any integer from 0 to |m| - 1 or 0 to -(|m| - 1).
37. I found that changing the values to 1 through 12 was easier and better, 
because with the other option you're only changing the display, the front, 
however with the first option you're changing the back end of the clock.

