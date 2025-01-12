# Roches Point Weather
**by: Phumi Tshidi**

<img src="https://i.pinimg.com/736x/06/58/37/0658377a91a1d68a9bb3cc2572175a7b--wind-sculptures-canopies.jpg" width="500" height="300">

# Key Sections

- **Overview:** Summary
- **Features:** Describes the files and their purposes.
- **Requirements:** Lists dependencies required to run the notebook.
- **Running the Jupyter Notebook:** Provides instructions for running the notebook using both Anaconda and Visual Studio Code.
- **Conclusion:** 

## Overview

This repository contains a Jupyter notebook that performs data analysis on wind speed dataset using Python-based data tools. The notebook demonstrates how to clean, process, and analyze wind speed data, providing insights and visualizations based on the dataset.

## Features

**Imports:** Required libraries for analysis

**Data Collection:** Import weather data from CSV file.

**Data Cleaning:** Handle missing values, normalize data, and prepare it for analysis.

**Statistical Analysis:** Compute averages, seasonal variations, and anomaly detection using `pandas and numpy`.

**Data Visualization:** Generate charts such as line plots and bar graphs to analyze trends using `matplotlib` or `seaborn`.

## Requirements

Before running the notebook, ensure you have the following installed:
- [Python](https://www.python.org/downloads/) (version 3.12 or higher) also available through anaconda.
- Jupyter Notebook
- [Anaconda] (https://www.anaconda.com/download) - recommended for managing environments
- [Visual Studio Code](https://code.visualstudio.com/) - for editing and running Jupyter notebooks

You can install all required dependencies by running:


## Running the Jupyter Notebook

There are two main ways to run the notebook: using **Anaconda** or **Visual Studio Code**.

### Running with Anaconda

If you're using Anaconda, follow these steps:

1. **Clone this repository** to your local machine:

    ```bash
    git clone https://github.com/PCM11/pfda-project
    ```

2. **Navigate to the project directory**:

    ```bash
    cd pfda-project
    ```

3. **Create a new Conda environment** (optional but recommended) with the necessary dependencies:

    ```bash
    conda create -n rochesp_weather python=3.12
    ```

4. **Activate the environment**:

    ```bash
    conda activate rochesp_weather
    ```

5. **Launch Jupyter Notebook**:

    ```bash
    jupyter notebook
    ```

    This will open Jupyter in your web browser. Navigate to `rochesp_weather.ipynb` and start working with the notebook.

###  Running with Visual Studio Code

If you prefer using Visual Studio Code:

1. **Clone the repository** to your local machine:

    ```bash
    git clone https://github.com/PCM11/pfda-project
    ```

2. **Navigate to the project directory**:

    ```bash
    cd pfda-project
    ```

3. **Open the folder** in Visual Studio Code:

    ```bash
    code .
    ```

4. **Install the Python extension** (if not already installed) in Visual Studio Code.

5. **Install the Jupyter extension** in Visual Studio Code.

6. **Open the Jupyter notebook** (`rochesp_weather.ipynb`) in Visual Studio Code, and the notebook interface will be available to run cells interactively.

- **Data analysis and visualization**: It processes the data using `pandas, numpy` and generates visualizations (using `matplotlib` or `seaborn`) to provide insights into wind speed trends.

## Conclusion

This notebook serves as a starting point for working with wind speed datasets or similar weather data. Future enhancements could include predictive modeling, more advanced anomaly detection methods, or integrating external datasets for richer analysis.
