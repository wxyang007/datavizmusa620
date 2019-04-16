---
title: "Plotting with altair"
date: 2019-04-19
tags: [dataviz, altair, musa-620]
excerpt: "Testing an altair interactive plot on jekyll."
custom-javascript-list:
  - https://cdn.jsdelivr.net/npm//vega
  - https://cdn.jsdelivr.net/npm//vega-lite
  - https://cdn.jsdelivr.net/npm//vega-embed
custom-css-list:
  - /assets/css/altair.css
header:
  teaser: "images/plotting-with-altair/altair_ico.png"
---

This library has recently caught my attention: [Altair](https://altair-viz.github.io). So here is a test check the interactive behavior on a post, can't wait to use more of it :).

### Code for the plot:

```python
import altair as alt
from vega_datasets import data
alt.renderers.enable('notebook')
```
