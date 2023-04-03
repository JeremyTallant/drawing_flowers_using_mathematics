# Phyllotaxis: Draw Flowers Using Mathematics
## Description
R is a tool for doing serious statistics and data analysis. But not everything in life can be serious, life is also beautiful, and R can make beautiful things too. R can make art.

The arrangement of leaves on a plant stem is ruled by spirals. This fact is called [phyllotaxis](https://en.wikipedia.org/wiki/Phyllotaxis) and it is a nice example of how mathematics can describe patterns in nature. In this project, we will invent flowers using this fact.
## Usage
Clone this repository and open the Jupyter notebook file (`*.ipynb`) in a Jupyter environment with R kernel support. Make sure to install the required packages such as `tidyverse`. You can do this by running the following commands in a code cell within the notebook:
``` r
install.packages("tidyverse")
```
Once the packages are installed, run the code cells in the notebook to generate the plots and analyses.

If you don't have a Jupyter environment set up, you can install Jupyter Notebook and the R kernel using the following steps:

1. Install Jupyter Notebook by following the instructions on the [official Jupyter website](https://jupyter.org/install).

2. Install the R kernel for Jupyter Notebook by running the following commands in your R console:
``` r 
install.packages("IRkernel")
IRkernel::installspec()
```
After completing the installation, launch Jupyter Notebook, navigate to the folder containing the notebook file, and open it to begin running the analyses.
## Contents
1. **Patterns in nature:** Set up the environment and load the ggplot2 package.
2. **Warming up: drawing points on a circle:** Create a scatter plot of 50 points arranged in a circle.
3. **Make it harmonious with the Golden Angle:** Create a spiralized scatter plot using the Golden Angle.
4. **Remove everything unnecessary:** Clean up the plot by removing unnecessary elements and changing the background color.
5. **A bit of makeup: size, color and transparency:** Enhance the plot's appearance by adjusting point size, transparency, and color.
6. **Play with aesthetics: the dandelion:** Transform the plot to resemble a dandelion by modifying point size, shape, and legend.
7. **Put all it together: the sunflower:** Generate a sunflower-inspired plot by altering point shape and colors.
8. **What if you modify the angle?:** Observe the effect of changing the angle value on the plot. 
9. **All together now: imaginary flowers:** Design a magenta flower plot by tweaking the angle, number of points, and aesthetics.