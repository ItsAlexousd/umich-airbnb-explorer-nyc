# Airbnb NYC Explorer 🗽

Welcome to the Airbnb NYC Explorer, a project developed as part of the "Python As An Engineering Tool" course at the University of Michigan-Dearborn. Dive deep into the world of Airbnb listings in New York City, visualize data, and gain insights from our interactive dashboard.

## 🚀 Features

- Interactive Dashboard: Explore Airbnb listings through an intuitive and interactive dashboard.
- Data Visualization: Visualize the geographic distribution of listings, price distributions, neighbourhood analysis, and more.
- Rent Estimation: Estimate rent based on various parameters like room type, neighbourhood, and address.
- In-depth Analysis: From hosts with the most reviews to neighbourhood price analysis, get a comprehensive view of the Airbnb landscape in NYC.

## 📦 Installation & Setup

1. Clone the Repository:

```bash
git clone https://github.com/ItsAlexousd/uofm-airbnb-explorer-nyc.git
cd uofm-airbnb-explorer-nyc
```

2. Install Dependencies:

```bash
pip install numpy pandas matplotlib plotly dash dash_bootstrap_components seaborn statsmodels scikit-learn
```

3. Run the Dashboard:

```bash
jupyter notebook airbnb-explorer-nyc.ipynb
```

Once the server is running, open your web browser and navigate to `http://localhost:8050`.

## 📊 Dataset

The dataset, `data/AB_NYC_2019.csv`, provides a comprehensive view of Airbnb listings in NYC. It includes details such as:

- Listing ID, name, host ID, host name
- Neighbourhood, room type, price
- Minimum nights, number of reviews, availability
- ... and more!

## 📝 Documentation

The code is thoroughly documented, with comments explaining each step. For a deep dive into the implementation, refer to the `airbnb-explorer-nyc.ipynb` file.

## 🌟 Results & Insights

- Visualize the geographic distribution of listings on a map.
- Analyze price distributions with histograms.
- Understand neighbourhood price dynamics.
- Discover the top hosts based on reviews.
- Estimate rents using various parameters.
