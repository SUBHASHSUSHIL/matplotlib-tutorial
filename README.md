# Matplotlib Tutorial

A hands-on, notebook-based tutorial covering the most common plot types and
customisation techniques in [Matplotlib](https://matplotlib.org/), Python's
foundational plotting library.

The tutorial is organised into **13 phases**, each focusing on a single chart
type or skill. Every notebook is self-contained and can be run independently.

---

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Project Structure](#project-structure)
- [Tutorial Outline](#tutorial-outline)
- [How to Use the Notebooks](#how-to-use-the-notebooks)
- [Key Concepts Covered](#key-concepts-covered)

---

## Prerequisites

- **Python 3.8+**
- A code editor or IDE with Jupyter notebook support (e.g. VS Code with the
  Python and Jupyter extensions, or JupyterLab)

## Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd matplotlib-tutorial
   ```

2. Create and activate a virtual environment:

   ```bash
   python -m venv .venv

   # Windows
   .venv\Scripts\activate

   # macOS / Linux
   source .venv/bin/activate
   ```

3. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Project Structure

```
matplotlib-tutorial/
├── README.md
├── requirements.txt
├── phase-01-setup-and-bar-plot.ipynb
├── phase-02-scatter-plot.ipynb
├── phase-03-histogram-plot.ipynb
├── phase-04-pie-plot.ipynb
├── phase-05-stem-plot.ipynb
├── phase-06-box-and-whisker-plot.ipynb
├── phase-07-stackplot.ipynb
├── phase-08-step-plot.ipynb
├── phase-09-fill-between-plot.ipynb
├── phase-10-subplots.ipynb
├── phase-11-saving-plots.ipynb
├── phase-12-custom-ticks.ipynb
└── phase-13-annotations-and-text.ipynb
```

## Tutorial Outline

| Phase | Notebook | Topic | What You Learn |
|-------|----------|-------|----------------|
| 1 | `phase-01-setup-and-bar-plot.ipynb` | Setup & Bar Plot | Environment setup, `plt.bar()`, colours, widths, grouped and horizontal bars |
| 2 | `phase-02-scatter-plot.ipynb` | Scatter Plot | `plt.scatter()`, custom markers, colour maps, colour bars, overlaying datasets |
| 3 | `phase-03-histogram-plot.ipynb` | Histogram | `plt.hist()`, bins, cumulative, horizontal, `rwidth` |
| 4 | `phase-04-pie-plot.ipynb` | Pie Chart | `plt.pie()`, explode, autopct, shadow, wedge props, donut chart |
| 5 | `phase-05-stem-plot.ipynb` | Stem Plot | `plt.stem()`, `linefmt`, `markerfmt`, `basefmt` |
| 6 | `phase-06-box-and-whisker-plot.ipynb` | Box Plot | `plt.boxplot()`, notch, orientation, labels, `showmeans`, multiple datasets |
| 7 | `phase-07-stackplot.ipynb` | Stack Plot | `plt.stackplot()`, stacked area for multi-series data |
| 8 | `phase-08-step-plot.ipynb` | Step Plot | `plt.step()`, `where` parameter, markers and grid |
| 9 | `phase-09-fill-between-plot.ipynb` | Fill Between | `plt.fill_between()` for shading between curves |
| 10 | `phase-10-subplots.ipynb` | Subplots | `plt.subplot()` grids combining multiple chart types |
| 11 | `phase-11-saving-plots.ipynb` | Saving Plots | `plt.savefig()`, DPI, format, face/edge colour |
| 12 | `phase-12-custom-ticks.ipynb` | Custom Ticks | `plt.xticks()` / `plt.yticks()` for text-based axis labels |
| 13 | `phase-13-annotations-and-text.ipynb` | Annotations & Text | `plt.text()`, `plt.annotate()` with arrows, legends |

## How to Use the Notebooks

1. Open the project folder in VS Code (or your preferred Jupyter environment).
2. Select the Python kernel from your virtual environment.
3. Run cells top to bottom within each notebook (`Shift + Enter`).

The notebooks are ordered sequentially but are self-contained, so you can
start at any phase that interests you.

## Key Concepts Covered

- **Chart types**: bar, scatter, histogram, pie, stem, box-and-whisker, stack,
  step, fill-between
- **Layout**: subplots and multi-panel figures
- **Export**: saving figures to image files (`savefig`)
- **Customisation**: custom tick labels, text annotations, colour maps,
  legends, fonts, and styling parameters throughout
