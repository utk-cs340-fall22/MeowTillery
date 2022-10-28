Sprint 2

Sean Kerzel, skerzel, Meowtillary

Planned: 
- Create a working sanity bar for the player 
- Create a hostile character health bar
- Hostile character dies upon empty health bar

Did not do: 
- I ended up not working on the hostile character and instead on the main character's systems

Problems: 
- After the character died, stopping all movement and particularly getting the death animation to play 
- Non damaging collision body's still cause main character to blink (a partial thing to indicate taking damage but I fixed it so they didn't actually take damage or trigger invincibility frames)

Issues: 
[#31](https://github.com/Jazny/Meowtillary/issues/31)
[#32](https://github.com/Jazny/Meowtillary/issues/32)
[#33](https://github.com/Jazny/MeowTillery/issues/33)

Files worked on: 
- Meowtillary/Blink.gd 
- Meowtillary/Blink.tscn 
- Meowtillary/HealthBar.gd 
- Meowtillary/HealthBar.tscn 
- Meowtillary/background_testing.tscn 
- Meowtillary/Hurtbox.gd 
- Meowtillary/Hurtbox.tscn 
- Meowtillary/PlayerStat.gd 
- Meowtillary/PlayerStat.tscn 
- Meowtillary/RigidBody2D.gd 
- Meowtillary/RigidBody2D.tscn 
- Meowtillary/SanityBar.gd 
- Meowtillary/SanityBar.tscn 
- Meowtillary/Sanitybarback.png (I made these 3 png's I didn't just download them) 
- Meowtillary/Sanitybarover.png 
- Meowtillary/Sanitybarprogress.png 
- Meowtillary/Spike.gd 
- Meowtillary/Spike.tscn 
- Meowtillary/Squango.tscn 
- Meowtillary/white_material.tres 
- Meowtillary/white.shader

Finished: 
- Working sanity bar and system for main character 
- Working health bar and system for main character which includes taking the damage, invulnerability frames, the blinking effect to show damage taken, and a changing health bar texture and some other small things 
- Made game send you to main menu after the character dies
