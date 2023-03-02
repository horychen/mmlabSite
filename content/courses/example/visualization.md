---
title: Visualization with DearPyGUI
date: '2021-01-01'
type: book
weight: 30
highlight: true
---

## Prerequisite

1. Learn how to do numerical integration/simulaiton

## Coding

We are going to visualize the state transtion of the Lorenz system with aid of DearPyGUI.

<!--more-->

<!-- ## Learn
{{< youtube hSPmj7mK6ng >}}
 -->

## Quiz

{{< spoiler text="Write Plotly code to render a bar chart" >}}
```python
import plotly.express as px
data_canada = px.data.gapminder().query("country == 'Canada'")
fig = px.bar(data_canada, x='year', y='pop')
fig.show()
```
{{< /spoiler >}}
