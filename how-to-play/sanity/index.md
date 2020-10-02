---
title: Sanity
---

# Sanity

Your sanity is a percentage and is displayed inside the truck. It drops when you are in darkness and if you witness ghost events.

## Low sanity

When your sanity is low it will increase the chances of a hunt. Your flashlight might also flicker randomly.

## Shade

If you look at a Shade ghost your sanity will drop very quickly.

## Recovering sanity

You can only recover sanity by using Sanity Pills.

## Tips

- have someone in the truck monitor your sanity and report if it is very low

## Advanced

<details>
  <summary>Click to reveal</summary>
  
  **This is technical information! It could spoil your play experience knowing too much about how the game works. This information is datamined and could change with future updates, not be implemented in the game, or not fully understood. Read below at your own discretion.**
 
  - When looking at a manifested ghost you lose sanity at the rate of `deltatime * ghost_sanity_strength` where all ghosts have a `ghost_sanity_strength` of 0.02 but Shade has 0.04 (It is unknown how or if this is changed at higher difficulties).
  - Sanity can never drop below 50% in Setup Phase.
  - Sanity drains slower in Setup Phase (0.09 vs 0.12).
  - Sanity meters in the van only update every 2 seconds.
  - Sanity meters in the van fluctuate from -2 to +3 of your actual sanity. EX: If I have 80 sanity the display could show between 78 and 83 sanity.
</details
