# Haxe expressions guide

## Introduction
Placeholder

## Examples

**Math.abs**  
Returns the positive value of a number: for example, if you write Math.abs(-25237), the result will be 25237.

It can also be used to calculate the distance between two numbers. For example:
Math.abs(100-200) will return 100.

**Math.round**  
Round the number to the nearest integer. If the numers ends with less than .5, 
the number will be rounded to the least integer, while if after the point there's a numebr equal to or 

greater than 5, the number will be rounded to the greater integer.

**Math.floor**  
This works like Math.round, but round only to the least and nearest integer number.
For example, Math.floor(5.2) is 5.

**Math.ceil**  
This only works like Math.floor (or Math.round) but round always for the greater integer.
So Math.ceil(3.9) will return 4.

**Math.sqrt**  
This evaluates the square root of a number, so produces a specified quantity when multiplied by itself.
for example, 5 is a square root of 25

**Math.PI**  
Math.PI is used to convert radians to degrees.
For example, to convert degrees to radians, you would do
degrees * (Math.PI / 180)

While to convert radians to deegres, you would do:
radians * (180 / Math.PI)

**Math.atan**  
This converts a position on X and Y axis into the amgle of that point's trajectory,
so it works so: Math.atan(X/Y). Warning: It only calculates the 180 degrees angle.

**Math.atan2**  
Thsi works like Math.atan unless 2 things:

1- you must write Math.atan2(Y, X) with a comma and not with a slash.  
2- This calculates the 360° trajectory angle.

Warning:
The y before the x is NOT a typo, it's just that way even though it
doesn't make sense.

**Math.sin**  
It oscillates the value between -1.0 and 1.0 on the Y-axis.
For example, Math.sin(10) is the sin of 10 radians.

**Math.cos**  
Math.cos works exacly as math.sin, except that this affects the X axis and not the Y.

**Math.min**  
If you write Math.min(2, 3) the expression will return the least number between the number you wrote.
For example: Math.min (2000, 3939) = 2000

Warning: if you give the same value like Math.min(100, 100) the result will be 100.

**Math.max**  
This is literally the opposite of Math.min:
If you write Math.max (100, 300), that will return 300 because is the greater number.
As in math.min if you give the same value 2 times the result will be that value itself.

**Math.asin**  
This code does the exact opposite of Math.sin; you give it a value (the height on the Y-axis, which must be between -1 and 1), and then the result will be the angle in
radians.

Warning: If you enter a number that is not between -1 and 1, the expression will return Math.NaN (not-a-number).

**Math.acos**  
Math.acos is identical to Math.asine, except instead of taking the Y axis it uses the X axis.
Warning: as in .asin, if you enter a number that is not between -1 and 1, the expression will return Math.NaN (not-a-number).

**Math.tan**  
This calculates the slope of the diagonal.

If you imagine a circle (made up of math.sin and math.cos), and imagine a diagonal that starts from the center of the circle and goes
outward, you can determine the slope of that diagonal with Math.tan(angle).

So Math.tan(angle) = Math.sin(angle) / Math.cos(angle)

**Math.exp**  
This expression raises a number called Napier's number, approximately 2.718, to the value specified in the expression.

Therefore, Math.exp(8) is equivalent to 2718 to the power of 8.
Therefore, Math.exp(x) is 2718 to the power of X.

**Math.pow**  
This is for powers.
For example, if you want to raise X to the power of Y, you would write Math.pow(X, Y).

So the expression looks like this:
Math.pow(base, exponent)
