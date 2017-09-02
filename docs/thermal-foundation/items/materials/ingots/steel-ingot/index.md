---
title: Steel Ingot
recipes:
  crafting:
    - ingot-steel-from-nuggets
    - ingot-steel-from-block
  smelter:
    - ingot-steel-from-dust-iron-and-coal-coke
    - ingot-steel-from-dust-iron-and-dust-coal
    - ingot-steel-from-dust-iron-and-dust-charcoal
    - ingot-steel-from-ingot-iron-and-coal-coke
    - ingot-steel-from-ingot-iron-and-dust-coal
    - ingot-steel-from-ingot-iron-and-dust-charcoal
    - dust-smelting-steel
    - recycling-axe-steel
    - recycling-bow-steel
    - recycling-fishing-rod-steel
    - recycling-hammer-steel
    - recycling-hoe-steel
    - recycling-pickaxe-steel
    - recycling-shears-steel
    - recycling-shield-steel
    - recycling-shovel-steel
    - recycling-sickle-steel
    - recycling-sword-steel
    - recycling-helmet-steel
    - recycling-chestplate-steel
    - recycling-leggings-steel
    - recycling-boots-steel
usage-recipes:
  crafting:
    - nugget-steel
    - gear-steel
    - storage-block-steel
    - axe-steel
    - bow-steel
    - fishing-rod-steel
    - hammer-steel
    - hoe-steel
    - pickaxe-steel
    - shears-steel
    - shield-steel
    - shovel-steel
    - sickle-steel
    - sword-steel
    - helmet-steel
    - chestplate-steel
    - leggings-steel
    - boots-steel
  pulverizer:
    - dust-steel
  compactor-plate:
    - plate-steel-from-ingot
  compactor-mint:
    - coin-steel-from-ingot
---

![Steel ingot](/assets/images/thermal-foundation/ingot-steel.png){:style="height: 128px"}


**Steel ingots** are raw materials made from
[iron](https://minecraft.gamepedia.com/Iron_Ingot) and
[coal](https://minecraft.gamepedia.com/Coal).


Obtaining
---------

### Crafting
{% include recipe-table.html type='crafting' recipes=page.recipes.crafting no-result=true %}

### Induction Smelter
{% include recipe-table.html type='smelter' recipes=page.recipes.smelter no-result=true %}


Usage
-----

### Crafting ingredient
{% include recipe-table.html type='crafting' recipes=page.usage-recipes.crafting %}

### Pulverizer ingredient
{% include recipe-table.html type='pulverizer' recipes=page.usage-recipes.pulverizer %}

### Compactor ingredient
{% include recipe-table.html type='compactor-plate' recipes=page.usage-recipes.compactor-plate %}

### Compactor with Numismatic Press ingredient
{% include recipe-table.html type='compactor-mint' recipes=page.usage-recipes.compactor-mint %}