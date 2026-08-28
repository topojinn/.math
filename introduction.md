Welcome in this guide about haxe expressions codes. 

Haxe is a programming language, but these expression isn't only avaiable on this language.
For example in python can be used by importing the module math.

(witch is pre-installed, so you hasn't to manualy immport it in the command palette) 

So, to create a simple calculator in python witch supports these codes, you can use this code:
```
import math

print("program started")
print("write any expression or operation\n")

text = input()

print("= ")
print(eval(text, {"math": math}))
```
**WARNING: EVAL IS EVIL! AN USER COULD INSERT A STRING WITCH CAN DAMNAGE THE COMPUTER!!**
