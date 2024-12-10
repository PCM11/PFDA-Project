# Roches Point Weather
**by: Phumi Tshidi**

<img src="https://i.pinimg.com/736x/06/58/37/0658377a91a1d68a9bb3cc2572175a7b--wind-sculptures-canopies.jpg" width="400" height="250">

# Key Sections

- **Overview:** Summary
- **Contents:** Describes the files and their purposes.
- **Requirements:** Lists dependencies required to run the notebook.
- **Running the Jupyter Notebook:** Provides instructions for running the notebook using both Anaconda and Visual Studio Code.
-**Usage Instructions:** Explains what the notebook does and how to interact with it.

## Overview

This repository contains a Jupyter notebook that performs data analysis on wind speed data using Python and the pandas library. The notebook demonstrates how to clean, process, and analyze wind speed data, providing insights and visualizations based on the dataset.

## Project Contents

- **wind_speed_analysis.ipynb**: A Jupyter notebook that contains the steps for analyzing wind speed data. The notebook includes data loading, cleaning, processing, and visualization using pandas.
- **data/**: A directory that contains the raw wind speed data (if included), or placeholder for dataset files.
- **requirements.txt**: A text file that lists all the Python dependencies required to run the notebook, including `pandas`, `matplotlib`, `numpy`, and others.
  
## Requirements

Before running the notebook, ensure you have the following installed:
- [Python](https://www.python.org/downloads/) (version 3.12 or higher) also available through anaconda.
- Jupyter Notebook
- [Anaconda] (https://www.anaconda.com/download) - recommended for managing environments
- [Visual Studio Code](https://code.visualstudio.com/) - for editing and running Jupyter notebooks

You can install all required dependencies by running:


## Running the Jupyter Notebook

There are two main ways to run the notebook: using **Anaconda** or **Visual Studio Code**.

### 1. Running with Anaconda

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

5. **Install dependencies** from `requirements.txt`:

    ```bash
    pip install -r requirements.txt
    ```

6. **Launch Jupyter Notebook**:

    ```bash
    jupyter notebook
    ```

    This will open Jupyter in your web browser. Navigate to `rochesp_weather.ipynb` and start working with the notebook.

### 2. Running with Visual Studio Code

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

5. **Install the dependencies** by opening a terminal in Visual Studio Code and running:

    ```bash
    pip install -r requirements.txt
    ```

6. **Install the Jupyter extension** in Visual Studio Code.

7. **Open the Jupyter notebook** (`rochesp_weather.ipynb`) in Visual Studio Code, and the notebook interface will be available to run cells interactively.

## How to Use

- **Load the dataset**: The notebook includes steps for loading wind speed data.
- **Data cleaning**: The notebook performs necessary cleaning operations, such as handling missing values or removing irrelevant columns.
- **Data analysis and visualization**: It processes the data using `pandas, numpy` and generates visualizations (using `matplotlib` or `seaborn`) to provide insights into wind speed trends.
