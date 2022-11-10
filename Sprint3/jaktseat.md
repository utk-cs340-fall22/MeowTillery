# Sprint 3

I am Jake Seaton, my github id is jakeseaton71, and I am a member of the Meowtillery group.

### What I planned to do
I was assigned to implement the following:
* Implement a dynamic camera system that will smoothly follow the player, rather than a static camera [Issue #55](https://github.com/Jazny/Meowtillary/issues/55).
* Implement a method for the player to destroy the turret bu jumping on the top of it [Issue #53](https://github.com/Jazny/Meowtillary/issues/53).
* Set up an animation player to play the character animations upon certain inputs and scenarios [Issue #44](https://github.com/Jazny/Meowtillary/issues/44).
* Implement a boss enemy that will pursue the player and fire bursts of projectiles at them [Issue #66](https://github.com/Jazny/Meowtillary/issues/66).

### What I was not able to do
I was able to achieve most of what I wanted to do.
The only part I was unable to complete was the turret destruction. When I was trying to program it, I was encountering issues with removing the turret from the level.
So, I decided to focus on the other elements instead.

### The problems I encountered
* Camera being too jittery
* Turret not properly being removed upon being jumped on.
* Player animations not playing correctly.
* Player death and jump animations not being times correctly.
* The boss enemy "Ingrid" not falling due to gravity.
* Ingrid jittering and teleporting towards the player instead of fireing.
* Ingrid's projectiles colliding with her hitbox.
* Ingrid not properly firing in bursts.

### Issues I worked on
* [Issue #55](https://github.com/Jazny/Meowtillary/issues/55).
* [Issue #53](https://github.com/Jazny/Meowtillary/issues/53).
* [Issue #44](https://github.com/Jazny/Meowtillary/issues/44).
* [Issue #66](https://github.com/Jazny/Meowtillary/issues/66).

### Files you worked on
* Meowtillery/CharMovement2.gd
* Meowtillery/Ingrid.gd
* Meowtillery/IngridProjectile.gd
* Meowtillery/IngridProjDamage.gd
* Meowtillery/Ingrid.tscn
* Meowtillery/IngridProjectile.tsn

### What you accomplished
I was able to fully implement the dynamic camera and the player animations. 
The camera will now follow the player with a slight smoothing effect.
The player will now properly play jumping, wall sliding, and death animations.
I was also able to implement a boss enemy that will persue the player and fire projectiles
in bursts of 5 when the player is within range. 