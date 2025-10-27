---
hide:
  - toc
title: "Page 2"
---

# A second page

Link to go back to the [main page](index.md).

## A table 

| Timetable   | Description                          |
| ----------- | ------------------------------------ |
| `Wednesday` | :material-check:     Learn to program|
| `Thursday`  | :material-check-all: Write thesis    |
| `Friday`    | :material-close:     Graduate        |

## a plot 

```
# mkdocs: render
import matplotlib.pyplot as plt
import numpy as np

xpoints = np.array([1, 8])
ypoints = np.array([3, 10])

plt.plot(xpoints, ypoints)
```
