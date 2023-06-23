# University of Michigan-Dearborn: Python As An Engineering Tool - Airbnb NYC Explorer

This repository contains code and data for the "Airbnb Explorer NYC" project. The project aims to explore and visualize data related to Airbnb listings in New York City.

## Installation

To run the code in this repository, you need to have the following dependencies installed:

- numpy
- pandas
- matplotlib
- plotly
- dash
- dash_bootstrap_components
- seaborn
- statsmodels
- sklearn

You can install these dependencies using `pip`:

```bash
pip install numpy pandas matplotlib plotly dash dash_bootstrap_components seaborn statsmodels scikit-learn
```

## Dataset

The dataset used for this project is available in the file `data/AB_NYC_2019.csv`. It contains information about Airbnb listings in New York City, including details such as the listing ID, name, host ID, host name, neighbourhood, room type, price, minimum nights, number of reviews, availability, and more.

## Usage

The main script for this project is `main.py`. It performs data analysis, visualization, and provides an interactive dashboard using the Dash framework.

To run the script, use the following command:

```bash
python main.py
```

The script will load the dataset, perform data preprocessing, generate visualizations, and start the Dash server. Once the server is running, you can access the interactive dashboard by opening your web browser and navigating to `http://localhost:8050`.

## Project Overview

The project performs the following tasks:

- Data loading and preprocessing
- Data exploration and visualization
- Price distribution analysis
- Neighbourhood analysis
- Host analysis
- Rent estimation

The code is well-documented and includes comments to explain each step. You can find the implementation details in the `main.py` file.

## Results

The project provides various visualizations and insights about Airbnb listings in New York City. Some of the key results include:

- Geographic distribution of housing on a map
- Price distribution histogram
- Neighbourhood price analysis
- Hosts with the most reviews
- Rent estimation based on room type, neighbourhood group, address, and other parameters
