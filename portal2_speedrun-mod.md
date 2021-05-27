

# Portal 2 speedrun script

## TODO
~~install newest version of speedrunmod~~
~~repulsion intro seam shot~~
turret factory open door portal - too hard, probably not worth
cave johnson
bind M4/M5 to quicksave
*column blocker reportal - hard, not worth*

### Pre game

1.  launch game
2.  launch livesplit
3.  setup sar:

`cl_showpos 1`  

`plugin_load sar`  
`sar_autorecord 1`  
`sar_speedrun_autostart 0`  
`ui_loadingscreen_transition_time 0`   
`sar_sr_hud 1`  
`sar_speedrun_time_pauses 0`  

`bind z "save quick"`  
`bind v "load quick"`  
`bind r "sensitivity 0.2"`  
`bind t "sensitivity 4.7"`  
`bind m "incrementvar mat_ambient_light_r 0 0.05 0.05;incrementvar mat_ambient_light_g 0 0.05 0.05;incrementvar mat_ambient_light_b 0 0.05 0.05"` (toggle ambient light)  
`bind mwheelup +jump`  
`bind mwheeldown +use`  

`alias moveslow "bind c movefast; cl_forwardspeed 84; cl_backspeed 84; cl_sidespeed 84"`  
`alias movefast "bind c moveslow; cl_forwardspeed 175; cl_backspeed 175; cl_sidespeed 175"`  
`bind c moveslow`  

#### some useful commands

`showtriggers_toggle`  
`load autosave`  (if loaded quicksave on accident)  
`host_timescale 0.5` (slow motion)  
`r_drawclipbrushes 2` - (cheat) draws most invisible walls in the game as purple or red boxes  

_bind MMB to Use_  
_bind Shift to Crouch_  

* * *

* * *

# Chapter 1

`map sp_a1_intro1`

1.  jump on button, then cube

## Three buttons _(Chamber 01)_

`map sp_a1_intro2`  

## Portal gun _(Chamber 02)_

`map  sp_a1_intro3`  

## Smooth Jazz _(Chamber 03/04)_

`map sp_a1_intro4`  

#### Part 1

1.  portal top left of the hole
2.  _cube just falls right onto the button_

#### Part 2

1.  Get one cube  
2.  Portal - **cross** of panels **above** and to the **right** of the **door**  
3.  shove the cube through the corner of the door

## Cube Momentum _(Chamber 05)_

`map sp_a1_intro5`  

1.  Button
2.  Portal stand
3.  Grab cube through quickly changing portals

## Future Starter _(Chamber 06)_

`map sp_a1_intro6`  

#### Part 1

1.  Portal stand
2.  Grab cube through quickly changing portals

#### Part 2

1.  Jump to **button** to the **left**
2.  Walk to the corner while holding **_A_** against the **glass**
3.  Zoom _**right dot of crosshair** is aligned with **right side** of **luminescence**(not entire light) of the single light on the opposite wall_
4.  Hold **_W_**
5.  _Fling to the exit_
6.  elevator on "please **return**"

## "Wheatley room" - Secret Panel _(Chamber 07)_

`map sp_a1_intro7`  

1.  **far right corner** of platform with orange portal
2.  stand on top of **block** that is **sticking out**
3.  portal through
4. **go LEFT!**

## "GLaDOS"

`map sp_a1_wakeup`  

_normal_

## Incinerator

`map sp_a2_intro`  

Land on **left side** of sticking pipe and **hold _A_**

_normal_

* * *

* * *

# Chapter 2

## Laser Intro _(Chamber 01)_

`map sp_a2_laser_intro`

1.  Stand in door
2.  Blue **furthest** white on the **left wall** as **high** as possible
3.  Orange on ground
4.  **Two jumps** and through the portal and **hold** **_A_** and **_W_**

## Laser Stairs _(Chamber 02)_

`map sp_a2_laser_stairs`  

1.  **Two portals** on top of each other on the right wall
2.  Portal near the **exit**
3.  Portal **under cube** and portal **under me**

## "Lasers and platform room" - Dual Lasers _(Chamber 03)_

`map sp_a2_dual_lasers`  

1.  Go up to the platform
2.  blue on **red dot**
3.  orange on laser on wall with exit
4.  Push against exit door and blue on **second panel** from the right and bottom **middle of bottom half** of the panel

## Laser Over Goo _(Chamber 04)_

`map sp_a2_laser_over_goo`  

##### easy approach

_normal_


## Catapult Intro _(Chamber 05)_

`map sp_a2_catapult_intro`  


## Advanced Aerial Faith-plates _(Chamber 06)_

`map sp_a2_trust_fling`  

1.  portal to **far far wall as high as possible**
2.  portal **through slanted surface**
3.  portal **up**
4.  press button
5.  jump onto the button
6.  rotate portal
7.  go back
8.  door

## Pit Flings (Companion Cube) _(Chamber 07)_

`map sp_a2_pit_flings`  

#### Stuck launch (easy?)

1.  orange on opposite wall, touching the bottom
2.  ang: **63**, straight
3.  **hold _S_ and shoot blue** to get stuck
4.  shoot blue in upper 3/4 of blue portal
5.  shoot **orange on left wall 4 times**, strafe onto platform
6.  walk into **corner**, aim at **brown uptick** in crack to button glitch - **hold _W_**
7.  fling

#### Triple reportal (hard?)

1.  **Reportal** twice
2.  portal **top right** corner of slanted platform and **reportal**

## Fizzler Intro _(Chamber 08)_

`map sp_a2_fizzler_intro`  

#### New strat
1. be fast
2. shoot under animated panes

* * *

* * *

# Chapter 3

## Ceiling Catapult _(Chamber 09)_

`map sp_a2_sphere_peek`

1.  **orange in the middle** of the wall and **jump on faithplate** and jump on ground to preserve momentum
2.  **orange under me near button** _(fall through and launch of faithplate)_
3.  **orange on the other side** _(while midair)_
4.  **blue under** right next to the wall under the button (press button while falling down)
5.  grab **cube** and aim it not 90\*
6.  **orange on wall** next to laser, **blue under** me
7.  **blue on slanted** surface - go through on top of the slanted surface
8.  **wallstrafe - jump - strafe - orange**, then **hold left**
9.  fix orange, blue laser

## Ricochet _(Chamber 10)_

`map sp_a2_ricochet`

1.  get cube
2.  orange on ground across pit close to the edge
3.  jump down with cube, blue under, let go of cube
4. blue on ground in front of big panel
5. land on ground - wait a moment - jump on faith plate
6. drop cube to get stopped by it and grab it

## Bridge Intro _(Chamber 11)_

`map sp_a2_bridge_intro`

1.  portal bridge **under button** (in the indent)
2.  activate button
3.  go grab **cube** and walk through portal
4.  portal near glass and **shove cube through the glass**
5.  portal to exit

## "Wheatley door egg room" - Bridge the Gap _(Chamber 12)_

`map sp_a2_bridge_the_gap`  

#### New fast route
1.   orange on ceiling
2. blue on floor near button
3. **press button**
4. **walk** (dont' jump) **into the blue portal**
5. **reportal on wall under cube as left as possible**
6. **orange under immediately** (not forward - directly down)
7. **grab cube**
8. **spam jump - scoll up**
9. **strafe right**


## Turret Intro _(Chamber 13)_

`map sp_a2_turret_intro`  

1.  _first turret ignore_
2.  orange behind turret, blue on near wall
3.  peek, blue
4.  180\*, orange under turret, blue on wall
5.  quicksave, orange on far wall,blue on floor
6.  orange in the middle of the right wall, blue on wall behind me
7.  jump, portal near camera, portal under, grab cube
8.  kill far turret with cube, portal under turret near exit
9.  ...

## "Under chamber room" - Laser Relays _(Chamber 14)_

`map sp_a2_laser_relays`  

1.  **third line** from right
2.  **fifth panel** from left

## Turret Blocker _(Chamber 15)_

`map sp_a2_turret_blocker`  

1.  portal **far far wall**
2.  portal bridge
3.  **stand in front** of bridge and portal and **jump** when turret starts shooting
4.  pick up turret and kill others, then pick up cube

## Laser vs Turret _(Chamber 16)_

`map sp_a2_laser_vs_turret`  

_normal way (bring back only normal cube)_

## "Nobel price winner room" - Pull the Rug _(Chamber 17)_

`map sp_a2_pull_the_rug`  

_normal way (swap cube on bridges)_

* * *

* * *

# Chapter 4

## "Surprise" - Column Blocker _(Chamber 18)_

`map sp_a2_column_blocker`

-   don't use bridge to block cube, jump and catch it (**wait 3 seconds**)


## Laser Chaining _(Chamber 19)_

`map sp_a2_laser_chaining`  

1.  get cube on the **left**
2.  portal to **right side** of room, aim cube, jump down
3.  **orange above faithplate**
4.  **blue** on nearest wall
5.  as you fall, blue on the floor - **top right** corner
6.  **orange top left** corner on the left white wall
7.  grab **cube** while falling down
8.  repeat 4. but blue on the floor - **bottom right** corner
9.  **strafe** to exit

## "Fancy laser room" - Triple Laser _(Chamber 20)_

`map sp_a2_triple_laser`  

1.  portal under cube, portal above exit
2.  portal on near wall (higher, not lower)
3.  go through and portal laser
4.  glitch, _go partially through door and glitch again (to trigger dialogue)_

## "Wheatley escape room - Jailbreak"

`map sp_a2_bts1`  

1.  _normal_
2.  orange on Wheatley wall, blue on far wall (against you)
3.  stand in orange
4.  when portals fizzle, replace them, go across and jump across when he says **"voice"**
5.  _normal (just a looooot of B-Hopping)_

* * *

* * *

# Chapter 5

## Turret Factory

`map sp_a2_bts3`  

_normal..._

#### turret range

1.  two portals on top of each other on right wall
2.  portal stand

#### inside

1. grab a turret
2. portal bump
3. replace turret

## Neurotoxin sabotage

_just B-Hop_

## GLaDOS again - Core

1.  Put Wheatley in the _opposite hole_
2.  Activate button (look at GLaDOS otherwise cutscene won't continue)
3.  Walk to the _opposite hole_ (quicksave)
4.  When you hear **"ding"**, jump on the closest ground
5.  push against the **back** of the elevator and **crouch**

* * *

* * *

# Chapter 6

`map sp_a3_00`  

## Underground

`map sp_a3_01`

1.  ...
2.  jump onto "KEEP OUT" sign and jump on wall pushing back
3.  line up portal (V)

## Cave Johnson

`map sp_a3_03`

1.  jump onto catwalk
2.  portal up
3.  **"cliff shot"**
4.  portal stand to bottom half of white surface
5.  portal on slanted surface
6.  portal strait
7.  portal just under **"P"** in AL**P**HA
8.  hold **_W_**
9.  portal **top right** corner
10. activate pump
11. jump to surface on the **left** and blue

## Repulsion Intro

`map sp_a3_jump_intro`

### New seam shot
[repulsion intro seam shot tutorial](https://www.youtube.com/watch?v=IONv8oDwzQE)
1. go up
2. **stand in corner**
3. **look in top left corner of white surface**
4. ang: **-19.91** **174.86**


#### part 2

1.  align with the middle/left part of duct
5.  **circle jump**
6.  place a **new portal** to go through (**crouch** while going through portal, crouch onto platform, **don't crouch on gel**)


7.  _normal_ ...

## Bomb Flings

`map sp_a3_bomb_flings`

1.  place orange while in elevator
2.  blue up
3.  orange portal stand onto **higher platform** in the chamber
4.  blue next to the button, jump and hit the button, strafe to the slanted surface
5.  orange on the slanted surface
6.  wait, jump, blue under gel, blue under me
7.  elevator **_"calcium"_**

## Crazy box - Wild cube

`map sp_a3_crazy_box`

#### Part 1

1.  portal under gel and top left corner of ceiling
2.  bounce onto **speaker**
3.  zoom in and shoot portal surface
4.  strafe into portal on the **right**
5.  shoot portal around the **corner** - **lower** part of white surface

#### Part 2

1.  portal under cube and under me, **crouch after going through portal**
2.  **turn portal funneling OFF *(G)***
3.  **orange top left corner of left part of white wall**
4. **blue under elevator not near wall**
5. **go through**
6. **hold crouch (and nothing else)**
7. **turn portal funneling back ON  *(H)***

## PotatOS

`map sp_a3_transition01`  

#### Part 1

1.  ...
2.  portal up to catwalk
3.  shoot **"portal helper"**

#### Part 2

1.  orange **as high as possible**
2.  blue nearer to wall **jump** in
3.  blue further to wall (strafe in if necessary)
4.  **don't hold any buttons**
5.  shoot blue under me

* * *

* * *

# Chapter 7

## Propulsion Intro

`map sp_a3_speed_ramp`  

1.  walk out to the right of the elevator
2.  **sixth leg** is covering **9** in 1**9**72
3.  orange pixel perfect white surface
4.  go inside and place **blue on ground**
5.  **reportal** to the ceiling - **hold left to not fall off**, go back
6.  place blue on ground
7.  jump in and **hold _W_**
8.  elevator on "we're **gonna** change the world"

## Blue and Orange - Prop Flings

`map sp_a3_speed_flings`

1.  blue on far panel
2.  **fall off**(don't jump) and jump off blue gel onto the pipe
3.  line up edge of the pipe strait
4.  shoot portal in the middle
5.  **hold _W_** and **scroll**
6.  elevator **_"again"_**

## Conversion Intro

`map sp_a3_portal_intro`  

Lemon skip

### New faster route

#### Part 1

`developer 1`  
`contimes 3`  

1.  portal strait up, portal right
2. Orange top left corner and  jump through
3. **Orange on line first stain from left** so that the portal is inside the wall (you can see lines orange lines on top and bottom)
4. **Blue on straight line**
5. Walk in and back out (hold crouch) - Cancel catapult trigger
6. Push against railing - pos: \* **944.07** \*
7. Align **left crosshair dot** with **small line** -  Shoot **blue**
8. Look towards **middle small lighter stain - it's top left corner** on right dark slanted surface
9. Hold ***A*** - get stuck
10. Shoot blue away
11. Shoot orange next to me
12. **2600 speed**
13. Hold ***D*** and shoot **Blue**

#### Part 2

1.  blue as high as possible
2.  go down and orange
3.  jump out onto elevator
4.  orange inside elevator
5.  blue down and jump down
6.  blue onto new high surface **not where plant is**
7.  **fix orange**
8.  **strafe left** to the door

## Three Gels

`map sp_a3_end`  

#### Part 1

1.  portal **high left side** of **right far** pillar, portal on floor
2.  **jump out of the portal, shoot high orange, strafe left, blue on floor**
3.  **stand on blue gel** _(where one small tile is sticking out)_, angle 45\*
4.  blue under, **hold crouch, strafe right**
5.  shoot **orange as far down as possible**
6.  jump and strafe onto the pipe, **align with white/black edge**
7.  hold **_W_**, vel: **2000, stop holding _W_ strafe right pass catwalk, then strafe left** a little bit (do a circle)
8.  orange **more down** on wall through catwalk
9.  jump down (**don't land on catwalk** - softlock) to where I was before
10. blue and stand in portal
11. **portal stand** - blue behind pipes
12. **tube bounce**
    1.  get on the top of the **middle pipe**
    3.  **forward and left** _look slightly down_
    4.  hold **_W_** and **look forward**
    5.  **when the tube curves push right**

* * *

* * *

# Chapter 8

## The Itch - Test

`map sp_a4_intro`  

#### Part 1 - Turret cubes

1.  Just put the cube on the button :D

#### Part 2 - "TEST"

_normal_

## Funnel Intro

`map sp_a4_tb_intro`  

1.  orange next to funnel
2.  blue on far side of white surface in funnel while **crouching on orange**
3.  **uncrouch, hold left, shoot blue, shoot orange**
4.  **funnel near turret-cube, grab cube, throw cube into orange**
5.  **blue down on opposite side, blue under cube**

## Ceiling Button

`map sp_a4_tb_trust_drop`

-   **_can't jump -> spam A-D_**
-   _don't go over 300 vel -> loose control_

1.  go through door
2.  jump to ceiling
3.  **hold crouch, "stand" on button and press it, strafe to grab cube**
4.  trigger button dialogue
5.  drop cube on yourself to go down
6.  activate with funnel
7.  elevator on **"trouble"** _(probably not fast enough)_

## Wall Button

`map sp_a4_tb_wall_button`

1.  **orange** on the **right** side of door, **blue, go through**
2.  **blue on other side**
3.  blue on the left
4. go through, **crouch**
5.  **grab cube, throw cube in mid air** - so it's further from me
6.  **stand up and go through portal**
8.  stand in doorway and throw the cube

## Chamber 04 - Polarity

`map sp_a4_tb_polarity`

1.  go through door
2.  jump to **ceiling**
3.  orange on funnel
4.  blue under, go up using funnel and loose Crouch-Fly
5.  elevator fast

## Chamber 05 - Funnel Catch

`map sp_a4_tb_catch`

1.  orange on right side in entrance
2.  blue on bot right corner of **top left panel**, stand in portal
3.  orange on far rod of gray surface above last floor dot
4.  **jump down, blue on wall, button,  grab cube**
5.  **jump** through portal, strafe right
6.  activate button, exit

## Chamber 06 - Stop the Box - 

`map sp_a4_stop_the_box`

1.  bridge
2.  jump **0.5 second** after cube falls onto faithplace and grab it
3.  shoot bridge down to block turrets
4.  jump down, place cube on button, portal up

## Chamber 11 - Laser Catapult

`map sp_a4_laser_catapult`

#### Alternate route to preserve Fly

1.  orange on **far back** wall on the **right**
2.  blue on **near left** wall
3.  portal stand onto slanted surface
4.  blue on floor
5.  **orange near left** corner of funnel so the **funnel doesn't go through**
6.  blue back on slanted
7.  hold **_W_** to go to front
8.  **Crouch-Fly** glitch, orange on floor
9.  use slanted surface to go up to ceiling
10. use back pipe to go down to exit _(or use near pipe - more difficult)_
11. elevator on **"crucial"** **(don't crouch!!!)**

## Chamber 12 - Laser Platform

`map sp_a4_laser_platform`

**don't jump**

#### Part 1

1.  orange on **bot left** corner of far wall
2.  "portal stand" blue to **opposite side**
3.  push the **button twice**, go quickly through portal and **catch the second cube**
4.  **throw** cube up, quickly **blue** on marked panel slightly **higher** off ground, **catch** cube
5.  orange on marked panel
6.  cube into blue so it aims up

#### Part 2 - long funnel

1. **ang:** \* **-30** \*
2. When Weatley sais "to your **left"** - **hold *W***
3. **strafe left**
4. If screen doesn't fade back in - hold crouch and S

## Chamber 15 - Prop Catch

`map sp_a4_speed_tb_catch`  

#### New route

1. turn **Portal funneling OFF**
2. **orange in far left corner of top left surface**
3. **blue under** and **hold _A_**
4. **blue next to ramp to clip small black panel** (bot right corner if small black panel)
5. **wall strafe**
6. do **2 speed wall strafes**
7. **jump off** - keep speed wall strafing - **CROUCH!**
8. **orange right under me at the last second**
9. **turn portal funneling back on (*H*)**

## Chamber 16 - Repulsion Polarity

`map sp_a4_jump_polarity`  

1.  ...
2.  orange top right of funnel
3.  crouch and blue under
4.  wait a sec, uncrouch
5.  orange low left
6.  blue in middle and strafe right
7.  use door to go down

* * *

* * *

# Chapter 9

## Finale1 - This is the part where he kills us

`map sp_a4_finale1`
1.   Fly, **don't jump**
1.  on the left wall above two larger panels is a hitbox
2.  jump to that
3.  fly straight
4.  follow walls - wallstrafe (look slightly away and hold sidekey)
5.  hit Wheatley panel(left side) to go down around left, **hit white wall trigger**
6.  follow catwalks
7.  behind door **jump under the catwalk above**
8.  land on top of catwalk, then **crouch and hold crouch**
9.  trigger crusher and wait

## Finale2

`map sp_a4_finale2`

1.  step off railing and crouch, **hold crouch**
2.  **don't go over 300**
3.  strafe around invisible wall
4.  go through **left side of the door** (still holding crouch)
5.  hit **yellow pillar** to stop
6.  go on right side of railing and **line up with left side of the yellow pillar**
7.  **uncrouch** and walk back
8.  strafe left between catwalk and turrets
9.  go down to far catwalk land on top of railing, **crouch**
10. go through **right side of door** (still holding crouch)
11. hide behind **yellow pillar**
12. **peek** turrets
13. right as their search **animation resets**, **GO - strafe left**
14. ...

## Finale3

`map sp_a4_finale3`

1.  orange behind door
2.  blue on near right, go through
3.  blue on far right
4.  ...
5.  orange **low left** next to the door
6.  blue up and jump through and **hit the top of the portal**
7.  **don't hit door**
8.  strafe follow catwalks
9.  shoot portal helper under gel pipe
10. blue on wall on the left and go through
11. wall strafe and continue strait, hit a sloped part to go down onto solid part of the wall
12. jump out to the left and hit ceiling
13. **go into funnel 'cause it's fast as f boiiiiiiii XD**
14. **press Use** key to put GLaDOS in

## Finale4

`map sp_a4_finale4`

#### Part 1

-   portal behind Wheatley
-   up on catwalk, on left side of the catwalk, **walk back and jump** on top of the railing, jump on right part of railing, after GLaDOS says "first" jump on left side of railing and jump and grab the core _(to not get pushed back)_  

#### Part 2

-   portal under Wheatley
-   go up again - go on other side, then jump for core

#### Part 3

-   blue on floor, orange behind - not where catwalk is (to the right, **the highest one**)
-   When GLaDOS says "this one should **do it**" - **blue under, ORANGE UNDER CORE, BLUE UNDER ME, BLUE UNDER WHEATLEY**
-   **Preserve portal** - spam orange on triangular piece of garbage
-   crouch on orange and shoot blue above button
-   **hold forward and hold LMB**

#### Practice moon shot

`drawline 192 192 1580 480 192 1580;drawline 480 192 1580 480 -96 1580;drawline 480 -96 1580 192 -96 1580;drawline 192 -96 1580 192 192 1580`
