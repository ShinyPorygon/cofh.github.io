---
title: Biocrude
image:
- alt: Biocrude
  file: thermal-foundation-2/biocrude.gif
recipes:
  crucible:
  - biocrude-from-biomass
  - biocrude-from-biomass-rich
  - biocrude-from-bioblend
  - biocrude-from-bioblend-rich
  transposer-empty:
  - bucket-biocrude
usage-recipes:
  transposer-fill:
  - bucket-biocrude
  refinery:
  - grassoline
redirect_from:
- /docs/thermal-foundation/biocrude/
- /docs/thermal-foundation-2/biocrude/
- /docs/1.12/thermal-foundation-2/biocrude/
---

**Biocrude** is a fluid obtained by melting down
[biomass](../pulped-biomass/) or
[bioblend](../pulped-bioblend/). It can be processed into
[grassoline](../grassoline/).


Obtaining
---------

### Magma Crucible
{% include recipe-table.html type='te-1-12-crucible' recipes=page.recipes.crucible %}

### Fluid Transposer
{% include recipe-table.html type='te-1-12-transposer-empty' recipes=page.recipes.transposer-empty %}


Usage
-----

Biocrude cannot be placed as a block.

### Fluid Transposer ingredient
{% include recipe-table.html type='te-1-12-transposer-fill' recipes=page.usage-recipes.transposer-fill %}

### Fractionating Still ingredient
{% include recipe-table.html type='te-1-12-refinery' recipes=page.usage-recipes.refinery %}
