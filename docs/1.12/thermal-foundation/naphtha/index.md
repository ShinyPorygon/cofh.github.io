---
title: Naphtha
redirect_from:
- /docs/thermal-foundation/fluids/fuel/naphtha/
- /docs/naphtha/
- /docs/thermal-foundation/naphtha/
- /docs/thermal-foundation-2/naphtha/
- /docs/1.12/thermal-foundation-2/naphtha/
recipes:
  refinery:
  - naphtha-from-crude-oil
  - naphtha-from-coal
  transposer-empty:
  - bucket-naphtha
usage-recipes:
  transposer-fill:
  - bucket-naphtha
  refinery:
  - refined-fuel
---

![Naphtha](/assets/images/thermal-foundation-2/naphtha.gif){:style="height: 128px"}


**Naphtha** is a fluid obtained by processing [crude oil](../crude-oil/) or
[liquifacted coal](../liquifacted-coal/) in a [fractionating
still](../../thermal-expansion/fractionating-still/). It can be used as fuel in a [compression
dynamo](../../thermal-expansion/compression-dynamo/), or processed into [refined
fuel](../refined-fuel/).


Obtaining
---------

### Fractionating Still
{% include recipe-table.html type='te-1-12-refinery' recipes=page.recipes.refinery %}

### Fluid Transposer
{% include recipe-table.html type='te-1-12-transposer-empty' recipes=page.recipes.transposer-empty %}


Usage
-----

Naphtha cannot be placed as a block.

### Fluid Transposer ingredient
{% include recipe-table.html type='te-1-12-transposer-fill' recipes=page.usage-recipes.transposer-fill %}

### Fractionating Still ingredient
{% include recipe-table.html type='te-1-12-refinery' recipes=page.usage-recipes.refinery %}

### Compression Dynamo fuel
When used as fuel in a [compression
dynamo](../../thermal-expansion/compression-dynamo/), a bucket of naphtha yields
1,000,000 RF.


Trivia
------

* Naphtha is internally registered as "refined oil".
