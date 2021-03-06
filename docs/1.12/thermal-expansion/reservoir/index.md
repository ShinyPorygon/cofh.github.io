---
title: Reservoir
redirect_from:
- /docs/reservoir/
- /docs/thermal-expansion/reservoir/
- /docs/thermal-expansion-5/reservoir/
- /docs/1.12/thermal-expansion-5/reservoir/
image:
- alt: Reservoir (Basic)
  file: thermal-expansion-5/reservoir-basic.png
- alt: Reservoir (Hardened)
  file: thermal-expansion-5/reservoir-hardened.png
- alt: Reservoir (Reinforced)
  file: thermal-expansion-5/reservoir-reinforced.png
- alt: Reservoir (Signalum)
  file: thermal-expansion-5/reservoir-signalum.png
- alt: Reservoir (Resonant)
  file: thermal-expansion-5/reservoir-resonant.png
- alt: Reservoir (Creative)
  file: thermal-expansion-5/reservoir-creative.png
recipes:
  crafting:
  - te-1-12-reservoir-basic
  - te-1-12-reservoir-hardened
  - te-1-12-reservoir-reinforced
  - te-1-12-reservoir-signalum
  - te-1-12-reservoir-resonant
---

A **reservoir** is an item that stores fluids. It is functionally similar to a
[bucket](https://minecraft.gamepedia.com/Bucket). It can also automatically
refill a player's equipment.


Obtaining
---------

### Crafting
{% include recipe-table.html type='crafting' recipes=page.recipes.crafting %}


Usage
-----

### Fluid storage
A reservoir can be filled and drained by hand, or automatically using a [fluid
transposer](../fluid-transposer/) or similar. It can be filled and drained at
rates up to 1,000 mB/t. A basic reservoir can store up to 10
[buckets](https://minecraft.gamepedia.com/Bucket) worth of fluid (10,000 mB).
This can be increased by upgrading the reservoir to a higher [tier](#tiers).

A reservoir can be in one of two usage modes: Fill and Empty. The current usage
mode of a reservoir can be switched by pressing "Cycle Item Mode" (V by default)
while holding it.

When a reservoir in Fill mode is used on a fluid source block, it picks the
fluid up like a bucket and stores it. When used in Empty mode, a filled
reservoir places one bucket worth of fluid in the world.

A reservoir can also be used on blocks that store fluids to fill or drain them.

### Refilling items
A reservoir can be activated and deactivated by using it while sneaking. When
active in a player's inventory, a reservoir automatically refills held and worn
items that can hold fluids.

If [Baubles](https://www.curseforge.com/minecraft/mc-mods/baubles) is installed,
reservoirs can be equipped as baubles in any slot.

### Dyeing
A reservoir can be dyed by combining it with a
[dye](https://minecraft.gamepedia.com/Dye) in a crafting grid. The dye can be
removed by placing the reservoir in a crafting grid.

### Enchantments
A reservoir can be enchanted with [Holding](../../cofh-core/holding/) to increase its
capacity.

| Holding level | Capacity multiplier |
|---
| I | × 1.5 |
| II | × 2 |
| III | × 2.5 |
| IV | × 3 |
{:.uk-table .uk-table-striped .uk-table-condensed .uk-text-small .cofh-table-compress}


Tiers
-----

Reservoirs come in six [tiers](../../thermal-foundation/tiers/).

{::options parse_block_html="true" /}
<div class="uk-overflow-container">
| Tier | Capacity | Note |
|---
| Basic | 10,000 mB |
| Hardened | 40,000 mB |
| Reinforced | 90,000 mB |
| Signalum | 160,000 mB |
| Resonant | 250,000 mB |
| Creative | N/A | Provides an unlimited amount of the fluid it stores. |
{:.uk-table .uk-table-striped .uk-table-condensed .uk-text-small .cofh-table-semi-compress}
</div>
{::options parse_block_html="false" /}
