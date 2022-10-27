# Sprint 2

I am Jake Seaton, my github id is jakeseaton71, and I am a member of the Meowtillery group.

### What I planned to do
I was assigned to implement the following:
* Implement a way of keeping track of the player's current state to be used to determine valid actions, which is [Issue #3](https://github.com/Jazny/Meowtillary/issues/3).
* Allow the character to be able to double jump and jump whilst moving, which is [Issue #22](https://github.com/Jazny/Meowtillary/issues/22).
* Implement a sliding wall jump, where the player can slide down a wall and jump off of it, and be able to horizontally dash, which is [Issue #24](https://github.com/Jazny/Meowtillary/issues/24).
* Implement a turret that will fire projectiles towards the player, which is [Issue #41](https://github.com/Jazny/Meowtillary/issues/41).

### What I was not able to do
I was able to achieve most of what I wanted to do.
The only part that I was unable to implement was the horizontal dash.
While I attempted to implement it, it was much more complicated to get it working right than I had initially thought, so I instead prioritized other issues over it.


### The problems I encountered
* Player wall jump coming to a stop too quickly and falling.
* Only running animations work.
* Turret crashing the program instead of firing.
* Turret projectile not detecting collision
* Turret projectile not colliding with walls or floor.
* Player could ride on the turret projectiles.

### Issues I worked on
* [Issue #3](https://github.com/Jazny/Meowtillary/issues/3).
* [Issue #22](https://github.com/Jazny/Meowtillary/issues/22).
* [Issue #24](https://github.com/Jazny/Meowtillary/issues/24).
* [Issue #41](https://github.com/Jazny/Meowtillary/issues/41).

### Files you worked on
* Meowtillery/CharMovement2.gd
* Meowtillery/Turret.gd
* Meowtillery/TurretProjectile.gd
* Meowtillery/Turret.tscn
* Meowtillery/TurretProjectile.tsn

### What you accomplished
I was able to completely redesign the player movement system in order to fix the numerous issues present with the previous implementation.
The player can now perform jumps while running, jump a second time in the air, and perform a sliding jump off of a wall.
I was also able to implement a stationary turret that will fire projectiles at the player when the player is within a set range.
These projectiles will damage the player on contact, and will be destroyed on contact with other surfaces.
