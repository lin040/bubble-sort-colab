# Bubble Sort Moving-Claw Visualizer

An interactive Bubble Sort demonstration designed for Google Colab. The complete visualization is generated and controlled by code—no prerecorded animation is used.

## Features

- Executes Bubble Sort step by step with the default array `[5, 2, 8, 1, 7, 3, 6, 4]`
- Moves two claws to each adjacent pair
- Opens, lowers, grips, lifts, swaps, releases, and resets the claws in sync with the algorithm
- Adjusts each claw's reach to the corresponding bar height
- Highlights the active C-code line
- Counts comparisons and swaps
- Supports pause, reset, shuffle, and speed controls
- Runs directly in a Colab output cell without additional package installation

## Run in Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lin040/bubble-sort-colab/blob/main/BubbleSort_Colab.ipynb)

Alternatively:

1. Download `BubbleSort_Colab.ipynb`.
2. Open [Google Colab](https://colab.research.google.com/).
3. Select **File > Upload notebook**.
4. Run the visualization cell.

## Customize the data

Edit the values at the top of the Colab code cell:

```python
INITIAL_VALUES = [5, 2, 8, 1, 7, 3, 6, 4]
AUTO_START = True
```

Use 4–10 integers for the clearest layout.
