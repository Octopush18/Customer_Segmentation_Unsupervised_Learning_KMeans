# Customer Segmentation Code

This code performs customer segmentation based on features such as age, annual income, and spending score. It utilizes the K-means clustering algorithm to group customers into distinct segments.

## Table of Contents
- [Overview](#overview)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Code Explanation](#code-explanation)
- [Results](#results)
- [Visualizations](#visualizations)

## Overview
This project reads customer data from a CSV file, preprocesses it, and performs customer segmentation using K-means clustering. It provides insights into customer groups based on age, annual income, and spending score.

## Usage
1. Make sure you have the required dependencies installed (see [Dependencies](#dependencies)).
2. Download the `Mall_Customers.csv` file and place it in the same directory as this script.
3. Execute the code in your preferred Python environment.

## Dependencies
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Install dependencies using the following command:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn

## Code Explanation

The code performs the following steps:

1. Imports necessary libraries: pandas, numpy, matplotlib, seaborn, and os.
2. Reads the customer data from "Mall_Customers.csv".
3. Renames the "Genre" column to "Gender".
4. Checks for missing values.
5. Generates various visualizations to explore the data.
6. Determines the optimal number of clusters using the Elbow Method for K-means.
7. Performs K-means clustering on different combinations of features (age vs. spending score, income vs. spending score, and all features).
8. Visualizes the clusters in 2D and 3D space.

## Results

The code outputs the labels assigned to each customer based on the clusters. It also displays the cluster centers for each feature combination.

## Visualizations

The code generates multiple visualizations including:

- Distribution plots for age, annual income, and spending score.
- Count plot for gender distribution.
- Bar plots for age groups, spending score ranges, and annual income ranges.
- Elbow plots to determine the optimal number of clusters.
- Scatter plots to visualize the clusters in 2D and 3D space.

For 3D visualization, clusters are represented in different colors.

