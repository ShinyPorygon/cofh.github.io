---
title: Itemduct
image:
- alt: Itemduct
  file: thermal-dynamics-2/itemduct.png
- alt: Itemduct (opaque)
  file: thermal-dynamics-2/itemduct-opaque.png
redirect_from:
- /thermal-expansion/items/itemducts/
- /thermal-expansion/transportation/itemducts/
- /docs/thermal-dynamics/ducts/itemducts/
- /docs/itemducts/
- /docs/itemduct/
- /docs/thermal-dynamics/itemduct/
- /docs/thermal-dynamics-2/itemduct/
- /docs/1.12/thermal-dynamics-2/itemduct/
recipes:
  crafting:
  - td-1-12-itemduct
  - td-1-12-itemduct-opaque
  - td-1-12-itemduct-opaque-from-transparent
  - td-1-12-itemduct-transparent-from-opaque
  - td-1-12-itemduct-dense
  - td-1-12-itemduct-vacuum
usage-recipes:
  transposer-fill:
  - td-1-12-itemduct-fast
  crafting:
  - td-1-12-itemduct-energy-one
  - td-1-12-itemduct-energy-three
---

An **itemduct** is a block that transfers items between blocks.


Obtaining
---------

A placed itemduct can be instantly picked up by dismantling it with a
[wrench](../../wrenches/). It can also be mined using a
[pickaxe](https://minecraft.gamepedia.com/Pickaxe).

### Crafting
{% include recipe-table.html type='crafting' recipes=page.recipes.crafting %}


Usage
-----

### Placement
When placed, an itemduct connects to any adjacent itemducts and blocks that can
output or receive items. Any connected side of an itemduct can be disconnected
and reconnected by using a [wrench](../../wrenches/) on it.

### Item transfer
When a block inserts items into an itemduct, the items are transported to the
nearest connected block that can receive them. An itemduct will not accept items
if they have nowhere to go.

Items in an itemduct gradually move towards their destination, at a speed of
half a block per second (40 ticks per block). The speed may be increased by
using [impulse itemducts](../impulse-itemduct/) and/or advanced
[servos](../servos/) and [retrievers](../retrievers/).

Dense and vacuum itemducts change the length of the path they are placed in,
which may affect item routing. A dense itemduct dramatically increases path
length, which decreases the priority of destinations behind it by default. A
vacuum itemduct dramatically decreases path length, which increases the priority
of destinations behind it by default. Note that the way items are routed may be
changed by [servos](../servos/) and [retrievers](../retrievers/).

### Attachments
Certain items can be attached to itemduct connections to change how itemducts
work. [Servos](../servos/) allow itemduct connections to pull items out of
blocks, [filters](../filters/) allow them to restrict which items may pass
through, and [retrievers](../retrievers/) allow them to pull items towards
themselves from other blocks connected to the network.

### Fluid Transposer ingredient
{% include recipe-table.html type='te-1-12-transposer-fill' recipes=page.usage-recipes.transposer-fill %}

### Crafting ingredient
{% include recipe-table.html type='crafting' recipes=page.usage-recipes.crafting %}
