# Sprint3

## What I planned to do
For sprint 3, we continued to work modularly.
My main tasks were to Implement a popup menu for the cat NPCs, add a health/hunger bar, and weaponize the NPC cats.
These were specified in issues #43 and #46.
I also assigned myself the task of implementing correct start positions for scene changes (issue #54)

## What I did not get to do
The one thing leftover was to implement issue #54 which was to correct start positions (x, y) for scene changes while the character is playing.
Solving issue #43 also invoked a new bug of the popup menu position in relation to the player (a finite state machine). 
These two must wait until next Sprint.

## Problems encountered
The main problem encountered this Sprint was merging all our different repo forks together.
This was mainly due to testing individual modules in shared scenes (and therefore changing the code).
We will avoid this in the future by only testing on copies of shared scenes and/or not doing "git add" on those scenes.

## Issues I worked on
#43: Create a new scene
#46: Popup menu for cats
#54: Exit makes Squango Apear on Entrance Door (still in-progress)

## Files I worked on
caged_grey_cat.gd
cat_popup.gd
caged_grey_cat_Area2D.gd
dungeon_to_bedroom.gd
bedroom_to_dungeon.gd

## Accomplished
I accomplished adding the artillery part of the game. We intended to do this early-on, but had to slowly learn the software and GD Script as we went. 
I also accomplished adding a new scene for the health replenishment. Next Sprint, I hope to have all of the implementations debugged and ready to present before the final presentation.
