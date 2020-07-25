# What is E+1
 a balance and qol features mod for _(well, technically a variant of)_ [Elona+](http://wanwanplus.blog.fc2.com/blog-entry-38.html)
 with which it is fully (ie. both ways) save compatible

# Usage
 unpack archived executable into matching E+ version directory

# Features
 #### Tweak AI
  - [x] accessible anywhere with tamer's whip
  - [x] adjust movement chance (10-100), prefered distance (1-5) and subroutine chance (0-35) (shows if sub is not defined)
  - [x] eating/pickup prohibtion
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
 * these appear after `Detect objects` use and during exploration (stepping on tiles marks features other than hidden medals)
 * additionally harvest job delivery chest are automarked
 #### Alchemical rain (when used by pet AI) will no longer spam restore spirit
 * randomly selects from: cure critical (triple chance), restore body/spirit, defender, hero, resistance, troll blood
 #### Stackables
 * crop produce (except wildflowers) - instead of increasing item +level, plot bonus transfers into harvest count multipliers (= level/5 + 1)
 * livestock produce (milk, eggs) - no suffix and always uncursed, note produce extracted by love potion remain unchanged
 * stackable jerky - no suffix
 
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
 #### Picnic basket
  * rotten ingredients not allowed in recipe
 #### Destiny loot
  * moved to chest (300s one) - still hardfixed godly but otherwise standard chest lootlevel rules apply, ie. itemlevel is inherited from chest

# Cutscenes (optional)
 * drop in translated `scene2.hsp` (eg. from E+C*) to exe directory
   ###### *not included, also note these are bit outdated but _should_ work, only failing silently on new scenes
  
# Planned
 #### Likely
 * port equipment set from OOR (partial, just one set)
 * port artifact fusion from OOR
 * more coherent napping mechanics and useful coffee
 * make enhant generation be more oo-like (ie. not nigh everything below godly tier being a slew of +skill bonuses)
#### Maybe
 * food jobs working as 'dish rankX or higher'

