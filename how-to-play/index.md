# How to Play

The objective of this game is to determine what kind of ghost is haunting the building. You do this by finding various forms of evidence and selecting them from your [Journal](#journal).

Each player spawns into a ghost hunting van loaded with equipment, sensors, a monitor and an explanation of the ghost and optional objectives.

Each player has 2 slots on their person to store items and 2 hands to carry items.

## Setup Phase

**Duration: 5 minutes (amateur difficulty)**

When your team is ready, pick up the main door key on the desk and open the front door. This starts the timer.

Use the Setup Phase to determine where the ghost is:

- look for cold breath in a room or hallway
- use the EMF Reader which shows you recent ghost activity
- speak its name loudly
- place candles and watch if they blow out
- search for fingerprints on doors, windows and light switches

After the 5 minutes ends, the ghost will at some point enter [hunting mode](#hunting-mode).

## Hunting mode

When the ghost wants to try to kill you, it enters a hunting mode. Your flashlights will flicker and the house lights will flicker for approximately 8 seconds. The front door will lock for the duration of the hunt.

After that, it will move through the house and if it is near you, could try and kill you!

### How to hide

- hide inside a closet or locker
- hide inside a room and close the door
- burn a Smudge Stick when the ghost is near you to give yourself more time to hide

### When does the hunt end

When the lights stop flickering then the hunt is over.

## Van

### Monitor

The monitor on the desk is used to look through the portable video cameras players can set up **and** any stationary cameras in the building. Every camera has a night-vision mode.

The ghost orb evidence is shown on the monitor. Leave a spare camera next to the monitor so a player can take a photo of the ghost orb.

### Whiteboard

The whiteboard explains optional objectives that give you money if you complete them.

It explains who the ghost is so you can say their name inside the building to anger them.

It explains if the ghost responds to everyone saying their name or only 1 person alone saying their name.

### Map

There is a live map of each player, where the stationary cameras are, where the power switch is and where any sensors are placed (which can be purchased when you are higher level).

### Sanity meter

Below the map is the level of sanity of each player. When players witness ghost events and spend time in the dark it will go down. Low sanity will make the ghost more powerful.

The only way to improve sanity is to consume sanity pills which is only available at higher levels.

### Sound sensors

At a higher level you can purchase sound sensors which are reported here.

### Activity

It informs you when the ghost is active inside the building. If it is high it means the ghost is probably moving around or interacting with objects.

**If the activity is at 10 then the ghost is hunting and you cannot use the radio from the van.**

#### Tips

- it is probably helpful to inform teammates of sudden jumps in activity in case it is a reaction to something they did

## Journal

When inside VR, reach over your right shoulder and grab or use (with trigger) to open your Journal. It explains everything about the game.

At the back of the Journal you can select your 3 forms of evidence then select which type of ghost it is. When you are satisfied you can end the round (below).

## Ending the round

One person should complete the evidence and select the ghost then press the keypad inside the van. Ensure everyone is inside the van.

## Evidence

See the [Evidence](/evidence) page.

## Sanity

Your sanity is a percentage and is displayed inside the truck. It drops when you are in darkness and if you witness ghost events.

If you look at a Shade your sanity will drop very quickly.

### Recovering sanity

You can only recover sanity by using Sanity Pills.

<details>
  <summary>Advanced</summary>
 
  - you lose sanity at the rate of `deltatime * ghost_sanity_strength` where all ghosts have a `ghost_sanity_strength` of 0.02 but Shade has 0.4
  - sanity can never drop below 50% in Setup Phase
  - sanity drains slower in Setup Phase (0.09 vs 0.12)
</details>

## Ghost Events

An optional objective is to witness a ghost event. It can be one of the following:

- seeing the ghost
- hearing the ghost walking or its voice
- seeing the ghost's footprints
- watching someone else die
