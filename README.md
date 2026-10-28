#Carnation invisible hitbox#

Explaining how simon might have did the collision hit box on carnation.

suspecting 2 types in my mind.
Which are :
  1, Collision group based
  2, body Velocity
  3, *Feel free to make a pr for your own concept*

#Explaining each methods

#1, Collision group based

So how this gonna work is that Carnation will have a huge box (called as hitbox).
Which is on collision group 8 <- can be any but uhh i like 8 (DONT ASK MY WHY)
and player usually should be around 0 or 1
The props should also be on the 8th collision group so that the carnation hitbox can move the props..

Advantages:
  Less code needed and less physics overhead (probably simon used this method??)

Disadvantages:
  Collisions may be innacurate and sometimes props can go out of bounds when they are pushed on the corners (bro is breaking the fourth wall)

#2, body Velocity (linear velocity or whatever u call)

Right right.
creating a body velocity ofcourse.
here carnation will run a loop where body velocity is being applied constantly on the carnation.
when the body velocity hits the prop they gets yanked away!

Advantages:
  Code should be written.
  Can decrease physics runtime intervals
  possible lags?

#3 https://create.roblox.com/docs/reference/engine/classes/BasePart (bro im lazy to do shit)
