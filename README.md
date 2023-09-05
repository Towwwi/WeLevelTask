## WeLevelTask

On player, We give the tag for Abilitysystemcomponent after 10sec delay.
ListenerActor has collision box -> if you hit collision box, it starts listening the changes on death -tag and sets the player as target.
We only change the tag on after 10sec delay, so you must collide with collisionbox, before the delay ends to receive the delegate

I wasnt sure can i use GAS or not to do this task, so I did it the way how i would do it on my own project (except i didnt use abilities for dying)
- I tried to keep it simple so I didnt think edge cases and pugs
- Also i did it on my breaks on work and after work so i didnt clean the code much (Its not that bad tho!)
  
