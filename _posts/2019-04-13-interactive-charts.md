---
title: "Interactive charts with altair and Observable"
date: 2019-04-13
published: true
tags: [dataviz, altair, musa-620]
excerpt: "Testing altair and Observable interactive chats on Jekyll."
custom-javascript-list:
  - https://cdn.jsdelivr.net/npm//vega@4
  - https://cdn.jsdelivr.net/npm//vega-lite@2.6.0
  - https://cdn.jsdelivr.net/npm//vega-embed@3
custom-css-list:
  - /assets/css/altair.css
altair-charts:
  vis: "altair/measlesChart.json"
observable-cells:
  url: https://api.observablehq.com/@nickhand/embedding-altair-plots-in-observable.js
  names: ["heatmap"]
toc: true
toc_sticky: true
---

This post will show examples of embedding interactive [Altair](https://altair-viz.github.io) charts and individual cells from [Observable](https://observablehq.com/).

## Altair Example

```python
import altair as alt
alt.renderers.enable('notebook')
```

<div id="vis"></div>

## Observable Example

<div class="fullwidth">
  <div id="heatmap"></div>
</div>
