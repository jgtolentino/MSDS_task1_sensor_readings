# MSDS Task 1: Sensor Readings Data Analysis

This repository contains the solution to Task 1P for the MSDS program, which involves analyzing a dataset of sensor readings taken every 5 minutes at 8 different locations between 2014 and 2015. The dataset includes temperature, light, and humidity readings. The tasks include data cleaning, analysis, and visualization using Python.

## Table of Contents

- [Task Overview](#task-overview)
- [Dataset](#dataset)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Tasks Breakdown](#tasks-breakdown)
- [Results](#results)
- [References](#references)
- [License](#license)

## Task Overview

This project is designed to perform the following tasks:

1. **Missing Data Identification**: Identify and count the number of missing entries in each feature of the dataset.
2. **Data Imputation**: Fill in the missing data using either the mean or median value of each feature, with a justification for the chosen method.
3. **Location Distribution**: Visualize the distribution of the "location" variable using a histogram and describe the findings.
4. **Categorical Encoding**: Encode the categorical variable "location" using an appropriate method, with an explanation of the chosen approach.
5. **Feature Scaling**: Apply min-max scaling to selected features and compare the distributions before and after scaling.

## Dataset

The dataset used in this project is available from the following link:

- [Sensor Readings Dataset](https://data.melbourne.vic.gov.au/api/explore/v2.1/catalog/datasets/sensor-readings-with-temperature-light-humidity-every-5-minutes-at-8-locations-t/exports/csv?lang=en&timezone=Asia%2FKolkata&use_labels=true&delimiter=%2C)

The dataset includes the following features:

- `boardtype`
- `boardid`
- `temp_max`
- `temp_min`
- `temp_avg`
- `light_max`
- `light_min`
- `light_avg`
- `humidity_min`
- `humidity_max`
- `humidity_avg`
- `location`

## Prerequisites

To run the code in this repository, you'll need the following:

- Python 3.x
- Jupyter Notebook
- Required Python libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/jgtolentino/MSDS_task1_sensor_readings.git
## Usage

To run the analysis:

1. Open the Jupyter Notebook:

   ```bash
   jupyter notebook

### How to Use:

1. **Copy the Markdown Content:**
   - Highlight the entire text above.
   - Copy the text by right-clicking and selecting **Copy**, or press `Ctrl + C` (Windows) or `Cmd + C` (macOS).

2. **Paste into `README.md`:**
   - Open your `README.md` file in a text editor or through GitHub's web interface.
   - Replace or append the existing content with this new Markdown content.
   - Save your changes.

3. **Commit and Push:**
   - Commit the changes to your repository with a relevant commit message.
   - Push the changes to GitHub to update the repository.

This Markdown content will correctly format the sections you provided for your `README.md`.

