---
title: Strongbox
image:
- alt: Strongbox (Basic)
  file: thermal-expansion-5/strongbox-basic.png
- alt: Strongbox (Hardened)
  file: thermal-expansion-5/strongbox-hardened.png
- alt: Strongbox (Reinforced)
  file: thermal-expansion-5/strongbox-reinforced.png
- alt: Strongbox (Signalum)
  file: thermal-expansion-5/strongbox-signalum.png
- alt: Strongbox (Resonant)
  file: thermal-expansion-5/strongbox-resonant.png
- alt: Strongbox (Creative)
  file: thermal-expansion-5/strongbox-creative.png
redirect_from:
- /thermal-expansion/items/strongbox/
- /docs/thermal-expansion/storage/strongboxes/
- /docs/thermal-expansion/storage/strongbox/
- /docs/strongbox/
- /docs/thermal-expansion/strongbox/
- /docs/thermal-expansion-5/strongbox/
- /docs/1.12/thermal-expansion-5/strongbox/
recipes:
  crafting:
  - te-1-12-strongbox-basic
---

A **strongbox** is a block that stores items. It is functionally similar to a
[chest](https://minecraft.gamepedia.com/Chest), but can be moved and
[secured](../../thermal-foundation/signalum-security-lock/). At higher [tiers](#tiers), it also
stores more items.


Obtaining
---------

A placed strongbox can be instantly picked up by dismantling it with a
[wrench](../../wrenches/). Its stored items and configuration are preserved in
the item. It can also be mined using a
[pickaxe](https://minecraft.gamepedia.com/Pickaxe), though this can be much
slower.

### Crafting
{% include recipe-table.html type='crafting' recipes=page.recipes.crafting no-result=true %}

### Upgrading
A strongbox is initially at the lowest [tier](#tiers) (basic). It can be
upgraded to higher tiers using [upgrade kits](../../thermal-foundation/upgrade-kits/) and
[conversion kits](../../thermal-foundation/conversion-kits/).


Usage
-----

### Placement
When placed, a strongbox faces the player. It can face any of the four cardinal
directions, and can be rotated using a [wrench](../../wrenches/).

### Manual usage
A placed strongbox is functionally similar to a
[chest](https://minecraft.gamepedia.com/Chest). When used, it is opened so that
items can be manually put in or taken out.

Strongboxes cannot store certain items that can themselves store items, like
other strongboxes or [satchels](../satchel/).

### Input and output
Items can enter and exit a strongbox through any of its sides.

### Security
A strongbox can have a [signalum security lock](../../thermal-foundation/signalum-security-lock/)
installed to restrict who can access it.

### Enchantments
A strongbox can be enchanted with [Holding](../../cofh-core/holding/) to increase its
capacity.

| Holding level | Capacity increase (slots) |
|---
| I | +9 |
| II | +18 |
| III | +27 |
| IV | +36 |
{:.uk-table .uk-table-striped .uk-table-condensed .uk-text-small .cofh-table-compress}

### Redstone comparators
When placed next to a strongbox with public access, a [redstone
comparator](https://minecraft.gamepedia.com/Redstone_Comparator) emits a signal
strength of between 0 and 15, depending on how full the strongbox is.


Tiers
-----

Strongboxes come in six [tiers](../../thermal-foundation/tiers/).

{::options parse_block_html="true" /}
<div class="uk-overflow-container">
| Tier | Capacity (slots) | Note |
|---
| Basic | 18 |
| Hardened | 36 |
| Reinforced | 54 |
| Signalum | 72 |
| Resonant | 90 |
| Creative | 1 | Provides an unlimited amount of the item it stores. |
{:.uk-table .uk-table-striped .uk-table-condensed .uk-text-small .cofh-table-semi-compress}
</div>
{::options parse_block_html="false" /}
