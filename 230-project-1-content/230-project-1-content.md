# Onwards and Downwards

## High Concept
Mine through an alien planet while collecting artifacts and fending off the local inhabitants.

## Genres
* Action
* Endless Runner
* Maze

## Platform
Mobile-friendly

## Story
> Carson mining company has bought the rights to this newly-indexed planet, at a high, but suspiciously affordable, price. Upon surveying it, they discover that it's infested with angry alien critters! Determined to recoup their investment and more, they send you, their first driller, to delve into the depths for the valuable crystals said to be overflowing the caverns of this planet."

While aliens on an unfriendly planet sounds like a spooky theme, the goal isn't to make fear play much of a part in the game. It should focus on moderately-quick action while collecting crystals, and take on a generally light tone. Over time, the aliens become more ferocious, and there will be more pressure mounting on the player to react quickly, but the focus will still be on excitement over fear.

## Esthetics

### Graphics style
Light, flat colors. Not too light, because I am not aiming for a cartoonish appearance, but something simple to keep visibility high on a cluttered screen.

### Sound
Fast-paced but simple music looping to complement the quick-reaction main gameplay, with a more relaxing theme to play in between exploration runs, while the player reviews their score and upgrades their equipment.

### Sound effects
* Ambient drilling: low machine engine hum
* Alien movement: many-legged footsteps that create a rapid tapping
* Alien attacks: swooshing/slashing noises with metal clangs for impact, accompanied by occasional screeches
* Ore-processing: light pings, similar to what one would expect from coin-gathering, but a little deeper and closer to a rumble
* Turret firing: small "pow" noises, similar to a dampened black powder shot (not so abrupt and harsh as a real gun), as well as a similar explosion noise for the projectile impact
* UI: Tap sounds for button feedback, maybe a heftier "ka-chunk" for the button that starts a run
* Background music alteration: As the player gets deeper into the planet, the background music should become deeper and more altered

## Gameplay

### Mechanics
* Driving: Control the drill to avoid enemies and collect crystals
* Powerups: Driving through or shooting power-up minerals will provide a temporary boost to an aspect of the drill
    1. Drill: Move faster, especially when going through solid ground (as opposed to open caverns)
    2. Refinery: Receive more money from ore collected
    3. Gun Turret: Increase rate of fire and damage, or a to-be-decided similar effect (triple-shot, area damage, etc.)
    4. Armor: Become temporarily impervious to damage, or heal up, or both
    5. Fuel: Replenish some fuel, allowing run to continue longer
* Enemies and fighting: Alien critters will roam the caverns, and chase down the player's drill, attempting to destroy it. The drill machine is equipped with a gun turret, which will automatically turn and fire at the nearest alien. If it is feasible within the game scope, there will be a variety of enemy types, including those that shoot at the player, tunneling enemies, and large bosses guarding extra-large crystal stashes. Depending on whether it is determined to be more fun, enemies may drop crystals or other money-rewarding loot upon death.
* Preparation: Between runs, the player can upgrade their drilling machine's five components (see Powerups), increasing their base effectiveness and maximum effectiveness. All components will start a run at minimum effectiveness. If it makes its way into the scope of the project, I would like to include the ability to purchase consumables, likely similar to or replacing powerups.
* Upgrades: When in a run, the player can use collected resources to enhance their drilling machine's components. These upgrades last for the length of the run, and may or may not cost the same resource that the player uses to tally score at the end of a run. Upgrades will have the same effect as during Preparation. For example: during Preparation, the player upgrades the Drill to rank 3, increasing its base speed value, and max speed value. The drilling machine will start out with that base speed, and during the run, upgrades to the drill can bring it up to the max speed. After the run, the drill is still rank 3, regardless of the amount of upgrades done during the run.
* Increasing difficulty environments: In general, as the player travels downward (which may be represented visually as upward for easier control and to minimize fingers obscuring the screen on mobile), the terrain will become tougher to drill through, slowing the player down. In addition, enemies will become stronger and faster, requiring a more beefy turret and skilled control to fend off. On the flip side, crystals will become more valuable.

### Control

#### Desktop:
* Movement: WASD/Arrows to steer the drill (forward, back, turn left/right)
* Upgrades: Clicking the relevant icon or pressing the associated hotkey will upgrade a component of the drill

#### Mobile:
* Movement: Holding on the screen causes the drill to drive and turn to aim towards the pressed location
* Upgrades: Tapping the relevant icon will upgrade a component of the drill

### Onboarding
The player will start out in a non-hostile zone, being supplied continuous fuel. They will be given the simple movement controls, and instructed to find and collect crystals. The basic controls are very recognizable, so players should have no difficulty understanding the movement. Then, the player will run into a cavern that has enemies, and the game will pause while another character panics and orders the player to come back, whereupon the drilling machine will be teleported to the surface. There, it will be explained to the player that this is how runs will end, and the player is given a gun turret on their drill, and thrown back into the action.

### Learning
As the number and strength of enemies increases, the player will need to master the driving controls to keep the drilling machine out of harm's way. Doing this will require learning how to backtrack along tunnels to kite and lose enemies between caverns, dodge attacks, and make the most use of powerups. For example, gathering enemies into a group by driving in circles before getting a gun turret boost would be a good way to clear out foes in a large area. Alternately, a player who gets a drill powerup could use it to clear new tunnels fast enough that they don't have to deal with foes chasing them, or grab loot from under large enemies' noses and escape before they can fight back. Furthermore, players will need to do all this while keeping track of regular fuel deposits, unless they want to run out of gas and end their run very quickly.

## Screenshots

### Main gameplay example:
![Main gameplay sketch][sketch1]

### Upgrade screen example:
![Upgrade screen sketch][sketch2]

## Other
Libraries: The only libraries I am requesting at this time are JQuery and JQuery UI. I can use JS all day, but please, no more:
```javascript
var listItemHTML = document.GetElementById("upgrade-list").firstChild.innerHTML;
```
Can't we agree that
```javascript
var listItemHTML = $("#upgrade-list li:first").html();
```
is a lot cleaner?

## About the developer
My name is Conner Catanese. I am a 3rd-year GDD student, and I like making games with math and bad art. My specialty would be website security, although I don't know how useful that will be in this project.

[sketch1]: Sketch1.png
[sketch2]: Sketch2.png