# CC-Excavate
Improved version of excavate built-in program

Based on [a built in program for turtles](http://www.computercraft.info/wiki/Excavate) that will mine out a specified width square of blocks, all the way down to bedrock level.

It will periodically return to the surface when it is full and drops off mined materials either into an available inventory placed behind it when it starts, or onto the ground. If fuel requirements are enabled, it will also periodically return to the starting point if it requires additional fuel.

__Improvement:__ move along every third layer and use the turtle.digUp and turtle.digDown commands to clear three layers at a time, which would save time and fuel. 

### Setup
```
pastebin get U1Fxke72 excavate
```

### Usage
```
excavate 16
```
