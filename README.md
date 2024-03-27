# Ad Clicks Analysis 

This repository contains Python code for analyzing ad clicks data and generating visualizations to compare the performance of two ad campaigns. The analysis is conducted using Jupyter Notebook.

## Table of Contents

- [Introduction](#introduction)
- [File Description](#file-description)
- [Analysis Steps](#analysis-steps)
- [Visualization](#visualization)
- [Conclusion](#conclusion)
- [Installation](#installation)
- [Dependencies](#dependencies)
- [Contributions](#contributions)
  
## Introduction

The primary objective of this analysis is to evaluate the effectiveness of different advertising platforms and compare the performance of two ad campaigns (Ad A and Ad B).

## File Description:
`ad_Analysis_(AB).ipynb`: Jupyter Notebook containing the Python code for the ad clicks analysis.
`ad_clicks.csv`: Dataset containing information about ad clicks, including user IDs, source platforms, experimental group assignments, and click timestamps.

## Analysis Steps:
1. **Data Loading and Exploration**:
   - The dataset (`ad_clicks.csv`) is loaded into a Pandas DataFrame.
   - The first few rows of the dataset are displayed to understand its structure.

2. **Platform Analysis**:
   - The number of views from each `utm_source` (advertising platform) is calculated.
   - The percentage of clicks from each `utm_source` is determined.

3. **Comparison of Ad Campaigns A and B**:
   - The number of users shown Ads A and B are compared.
   - The percentage of users clicking on Ads A and B is calculated.

4. **Daily Analysis**:
   - The analysis is further refined to compare the clicks on Ad A and Ad B on a daily basis.
   - Visualizations are generated to illustrate the daily performance of both ad campaigns.

## Visualization

The analysis includes visualizations to provide insights into the performance of ad campaigns over time.
The visualizations help in understanding the variation in click rates and identifying any patterns or trends.
  
## Conclusion

Based on the analysis, recommendations regarding the choice between Ad A and Ad B can be made, considering factors such as click-through rates and performance over time.

## Installation

Ensure that you have Python and Jupyter Notebook installed on your system.
Download the `ad_Analysis_(AB).ipynb` and `ad_clicks.csv` files from this repository.
Open the Jupyter Notebook (`ad_Analysis_(AB).ipynb`) using Jupyter Notebook.
Run each cell in the notebook sequentially to execute the code and generate the analysis results.

## Dependencies
- Python 3.12.0
- Jupyter Notebook
- Pandas
- Matplotlib

## Contributions

Contributions are welcomed!
