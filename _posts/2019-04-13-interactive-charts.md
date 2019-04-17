---
title: "Interactive charts with altair and Observable"
date: 2019-04-13
published: true
tags: [dataviz, altair, musa-620]
excerpt: "Testing altair and Observable interactive chats on Jekyll."
altair-loader:
  altair-chart: "charts/measlesAltair.json"
observable-loader:
  url: https://api.observablehq.com/@nickhand/embedding-altair-plots-in-observable.js
  names:
    vega-chart: "heatmap"
html-loader:
  holoviews-chart: "charts/measlesHoloviews.html"
toc: true
toc_sticky: true
---

This post will show examples of embedding interactive [Altair](https://altair-viz.github.io) charts and individual cells from [Observable](https://observablehq.com/).

## Altair Example

```python
import altair as alt
alt.renderers.enable('notebook')
```

<div id="altair-chart"></div>

## Observable Example

<div class="fullwidth">
  <div id="vega-chart"></div>
</div>

## Holoviews Example

<div id="holoviews-chart"></div>
