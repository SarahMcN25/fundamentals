# **Fundamentals Project**
## Author: Sarah McNelis - G00398343

***
<br>

## Overview

This repository contains the following two jupyter notebooks:

1. pyplot.ipynb contains an overview of the matplotlib pyplot python package and an in-depth explanation of three plots.

2. cao.ipynb explains how to load the CAO points information from the official website into a pandas data frames and compares the CAO points from 2019, 2020 and 2021.

<br>

***

<br>

## requiremnet.txt
This is a text file that contains a list of all the packages requried to import in order to run this notebook. 

<br>

***

<br>

## How to run a [jupyter notebook](https://jupyter.org/):

1. Download [Anaconda]().
2. Download [cmder]() if on windows.
3. Run `jupyter lab` on the command line. 

<br>

***

<br>

## Quick steps

### NB viewer
[Nbviewer](https://nbviewer.org/) is an online tool created by the Jupyter community for rendering notebooks in static form.

You can view both notebooks on nbviewer by clicking on the following badge:

[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/SarahMcN25/fundamentals/tree/main/)


### Binder
Mybinder is an online service where you can share a notebook in a dynamic and interactive way.

You can view these notebooks on mybinder by clicking on the following badge:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/SarahMcN25/fundamentals/HEAD)

<br>

***

<br>

# 1. Pyplot Notebook

## The Matplotlib Pyplot Package
Matplotlib pyplot is a state based interface used for data visualisation. It is a convenient way for users to generate high quality plots with minimal effort. Pyplot can define and store the current state using various commands and functions. This package has 137 functions that can be used for plotting. In order to demonstrate how pyplot works this notebook explains for following plots in detail. 

### - Horizontal Bar Plot
This function takes data and plots it using horizontal bars. It has 5 parameters; y, width, height, left, align. The example in the notebook uses numpy random to generate data for y values and for the width values. Then other pyplot functions are used for example:
- yticks sets the ticks and labels on each of the horizontal bars.
- gca is used to invert the y-axis so that the place names match with the data generated for those cities.
- xlabel is used to put a label on the x-axis
- title adds a title to the plot
- show is used to call and display the horizontal bar plot.
- savefig is used to save the figure as a png file. 

<br>

![barh_png](Horizontal_Bar_Plot.png)

<br>

### - Scatter Plot
This function contains the following parameters; x, y, s, c, marker, cmap, norm, vmin, vmax, alpha, linewidths, edgecolors, plotnonfinite. This scatter plot uses the numpy random function again to generate values for x and y. It also generates random color values while also producing random sizes for the markers. As shown here, there are various sizes and colors used in this plot while alpha allows for slight transparency. Along with the scatter plot, these two other pyplot functions are used:
- show is used to call and dsplay the scatter plot.
savefig is used in order to save this figure as a png file. 

<br>

![scatter_png](Scatterplot.png)

<br>

### - Histogram
Histograms uses these parameters; x, bins, range, density, weights, cumulative, bottom, histtype, align, orientation, rwidth, log, color, label, stacked. The histogram created in this notebook displays 10000 random values of mean and standard deviation in normal distribution. In other words, various mu and sigma values are passed into the argument as x and are plotted in a bell shaped curve. Other pyplot functions are used here for example:
- xlabel sets the mu value label on the x-axis.
- ylabel describes the sigma values on the y-axis.
- title gives a title of the overall plot. 
- text allows the user to add a text line on the plot at particulat coordinates. 
- xlim sets the limits on the x-axis from left to right.
- ylim sets the limits on the y-axis from bottom to top.
- grid displays the plot on a grid.
- show is used to call and display the histogram. 
- savefig is also used here to create a png for this figure. 

<br>

![histo_png](Histogram.png)

<br>

***

<br>

## 2. CAO Notebook





<br>

***

<br>

## **Conclusion**
This readme contains a quick overview of two notebooks. 



<br>

***

<br>

## References

All references and code used in this notebook have been sourced in Oct/Nov 2021 from the following webpages:

- 


