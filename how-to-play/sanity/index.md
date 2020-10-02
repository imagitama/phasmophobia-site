---
title: Sanity
---

# Sanity

Your sanity is a percentage and is displayed inside the truck. It drops when you are in darkness and if you witness ghost events.

## Low sanity

When your sanity is low the ghost gets stronger.

You might also hear a heartbeat sound and your flashlight might randomly flicker.

## Shade

If you look at a Shade ghost your sanity will drop very quickly.

## Recovering sanity

You can only recover sanity by using Sanity Pills.

<details>
  <summary>Advanced</summary>
 
  - you lose sanity at the rate of `deltatime * ghost_sanity_strength` where all ghosts have a `ghost_sanity_strength` of 0.02 but Shade has 0.4
  - sanity can never drop below 50% in Setup Phase
  - sanity drains slower in Setup Phase (0.09 vs 0.12)
</details

## Tips

- have someone in the truck monitor your sanity and report if it is very low
