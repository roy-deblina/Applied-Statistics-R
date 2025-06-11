# Data Analysis Project

This repository contains my final exam project for the R programming and statistical analysis course. The exam consists of five sections covering vector operations, user-defined functions, data visualization, and distribution analysis using base R. Each section demonstrates practical application of statistical methods on synthetic and real datasets.

## Overview

This project contains a complete R-based statistical analysis conducted as part of a final exam exercise. It is divided into **five sections**, each covering different foundational topics in R programming and statistical data analysis. The `.Rmd` file includes code, inline outputs, and visualizations, and is rendered into HTML for submission and documentation purposes.

All work is performed in **base R**, and no additional libraries are used unless otherwise stated.

## File Structure

- `Final_Exam_Analysis.Rmd` - Source R Markdown file containing all code, explanations, and outputs
- `Final_Exam_Analysis.html` - Rendered HTML version of the analysis

## Sections Breakdown

### Section 1: Vector Manipulations (8 points)
- Constructs a custom vector with mixed elements (sequences, repetitions, arithmetic sum)
- Performs sorting, vector addition with descending sequences, subsetting
- Reconstructs vectors and computes the final sum

### Section 2: Trigonometric Function and Plotting (10 points)
- Defines and applies a trigonometric function:  
  `y = sin(x) + cos(x/2)`
- Computes the value of `x` corresponding to the maximum `y`
- Visualizes the function using base R plotting and annotates the maximum point

### Section 3: Function Intersection (8 points)
- Compares two functions:  
  `y1 = cos(x/2) * sin(x/2)` and `y2 = -(x/2)^3`
- Detects the closest point of intersection numerically
- Plots both functions and highlights the intersection point with labels

### Section 4: Trees Dataset Analysis (12 points)
- Uses the built-in `trees` dataset
- Computes median values and subsets data using logical indexing
- Converts diameter to radius and calculates area
- Displays:
  - Stem-and-leaf plot
  - Histogram of radii
  - Scatterplot of area vs radius
  - Notched boxplot of area
- Identifies if the largest tree is an extreme outlier using the 3×IQR rule

### Section 5: Distribution Comparisons (12 points)
- Generates:
  - Normal data sample using `rnorm()`
  - Exponential data sample using `rexp()`
- Computes interquartile range (IQR) for both distributions
- Visualizes distributions with:
  - Histograms
  - Boxplots
  - QQ plots
- Checks for extreme outliers using `boxplot.stats(..., coef = 3)`

# Learning Objectives

- Practice data manipulation, transformation, and subsetting in R
- Work with user-defined functions and apply them to sequences
- Gain proficiency in base R plotting techniques
- Analyze and visualize real-world datasets
- Compare statistical properties of different distributions

# Acknowledgements

- Dataset: `trees` — built-in R dataset on black cherry trees
- Developed as part of coursework at Northwestern University (Data Science program)
