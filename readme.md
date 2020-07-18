# What is E+1
 a balance and qol features mod for _(well, technically a variant of)_ [Elona+](http://wanwanplus.blog.fc2.com/blog-entry-38.html)

# Features
 #### Tweak AI
  - [x] accessible anywhere with tamer's whip
  - [x] adjust movement chance (10-100), prefered distance (1-5) and subroutine chance (0-35) (shows if sub is not defined)
  - [x] eating/pickup prohibtion
  - [ ] add some aesthetic polish to ui
  - [ ] disable options covered from Leold dialogue
 #### Healbots (inspired by E+C)
  * allies with `Healing Rain` set as low hp action will use it for others that are below 50% hp
  * much like in E+C, but only used when in effective range
 #### Mass Commands
  * press mode key _(default z)_ in `Directive` ally picker to instruct all
  * press mode/inventory keys _(default z/x)_ in `Call ally` picker to dismiss/call all
 #### Mirror (skill) shows base resistances
 #### Tweak AI / Mirror / Info
 * are also accessible in home area from interact menu
 #### Quest HUD for Party Time/Harvest jobs (port from OOR)
 * displays time left and accumulated points/delivered weight
 #### Cooking works akin to sense quality for foodstuffs
 * partial identify and only at item creation - no periodic checks
 #### Inventory food rot timer (port from OOR)
 * food rot timers available at partial identify (from cooking skill)
 #### Displace (most) talkable NPCs with shift-move (port from OOR)
 #### Filter 'undecoded' books from reading (port from E+C)
 #### Minimap markers (partial port/rewrite from OOR)
 * these appear after `Detect objects` use
 
# Rebalance
 #### Sleep
  * sleep time is proprotional to tiredness level (= limit( tiredness/2, 7, 16 ) )
 #### Travel (and napping)
  * `Magic Locomotive` is as fast as `Truck` on road (ie. has 9/25 of movecost modifier everywhere)
  * overmap travel napping only occurs when sleepy
  * world vehicle tier increases chance of travel napping (from 20% with no vehicle to 100% with battleship)
  * removed chance of tiredness counter not increasing when traveling on overmap
 #### Breakfast
  * instead of whopping 6 stat exp (at max cooking roll), breakfast now gives scaling growth buff (much like Inkeepers Special)
  * +(5*tier)% for 1500 turns, with cooking thresholds rescaled to increase tier spacing to more E+ appropriate levels (+50%)
 #### Thirst
  * walking on water type tiles quckly replenishes hydration

# Cutscenes (optional)
 * drop in translated `scene2.hsp` (eg. from E+C*) to exe directory
   ###### *note these are bit outdated, but should work
  
# Planned
 #### Likely
 * stackable jerkys and milk (no suffix, uniform satiety value)
 * port equipment set from OOR (partial, just one set)
 * port artifact fusion from OOR
 * more coherent napping mechanics and useful coffee
#### Maybe
 * food jobs working as 'dish rankX or higher'
 * crops that dont benefit from +enhance lose it (coffee, tea, tobacco, ??)
#### Unlikely
 * partly stackable crops (+enhance limited to +3 with overflow carried to yield - eg. +6 -> +3*2)

