# Sprint 1

I am Jake Seaton, my github id is jakeseaton71, and I am a member of the Meowtillery group.

### What I planned to do
I was assigned to implement the following:
* Left and right character movement from the user input, which is [Issue #2](https://github.com/Jazny/Meowtillary/issues/2).
* Character jumping movement and realistic gravity, which is [Issue #6](https://github.com/Jazny/Meowtillary/issues/6).

### What I was not able to do
I accomplished the basic level of each item I planned to do, but there are some implements that I was not able to accomplish for this sprint.
These implements are:
* Only being able to jump when on the ground.
* Being able to jump while moving. 

### The problems I encountered
* Gravity system would constantly increase downward velocity even when you were on the ground.
* Jumping while moving breaking animations.
* Jumping animation not playing properly.
* Character would not slow down after traveling in a direction.
* Gravity being too high or too low.

### Issues I worked on
* [Issue #2](https://github.com/Jazny/Meowtillary/issues/2).
* [Issue #6](https://github.com/Jazny/Meowtillary/issues/6).

### Files you worked on
* Meowtillary/RigidBody2D.gd

### What you accomplished
(Give a description of the features you added or tasks you accomplished. Provide some detail here. This section will be a little longer than the bulleted lists above) 
I was able to implement the basic movement system for the main character, known as Squango for the time being. The user can move the character to the left
and right using A and D, or the left and right arrow keys. The character will quickly slow to a stop when the button is not pressed. The character can
also jump using the spacebar. Upon jumping, the character will shoot into the air and accelerate towards the gound until reaching a terminal velocity.
The character will also fall off of ledges when walked over. The character sprite will also change to reflect these movements.