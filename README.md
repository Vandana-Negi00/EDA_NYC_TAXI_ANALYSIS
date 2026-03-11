
# NYC Yellow Taxi Trip Data – Exploratory Data Analysis

## Project Overview

This project performs Exploratory Data Analysis (EDA) on the New York City Yellow Taxi Trip dataset for the year 2023. The objective is to explore taxi trip patterns, understand passenger behaviour, and analyse key variables such as trip distance, passenger count, and payment methods.

The project demonstrates the complete EDA workflow including data loading, preprocessing, cleaning, visualization, and interpretation of results using Python.

---

## Objective

The primary goal of this project is to analyse NYC taxi trip data to identify patterns and insights that can help improve operational efficiency and understand taxi usage behaviour.

The analysis focuses on:

* Understanding the distribution of trip distances and passenger counts
* Identifying missing values and handling them appropriately
* Detecting outliers in important numerical variables
* Analysing relationships between key variables
* Visualising taxi trip patterns using statistical plots

---

## Dataset

The dataset used in this project is the **NYC Yellow Taxi Trip Data (2023)** published by the New York City Taxi and Limousine Commission (TLC).

Dataset source:
[https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)

The dataset contains information about taxi trips including pickup time, drop-off time, passenger count, trip distance, fare details, and payment type.

### Key Variables

* VendorID
* Pickup datetime
* Dropoff datetime
* Passenger count
* Trip distance
* Pickup location ID
* Dropoff location ID
* Payment type
* Fare amount
* Tip amount
* Tolls amount
* Total amount

---

## Tools and Technologies

The analysis was performed using the following tools and libraries:

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Methodology

### Data Loading

Monthly taxi trip data files were loaded and combined into a single dataset for analysis. Sampling was performed to manage memory usage and improve processing efficiency.

### Data Cleaning

Data preprocessing steps included:

* Resetting the dataset index
* Handling duplicate or inconsistent columns
* Treating missing values using statistical methods
* Preparing the dataset for analysis

Missing values were handled as follows:

* Passenger count replaced using the mode
* RatecodeID replaced using the mode
* Congestion surcharge replaced using the median

### Outlier Detection

Outliers were examined in key variables such as trip distance, passenger count, and fare amount using box plots and statistical summaries.

---

## Exploratory Data Analysis

The dataset was analysed using different EDA techniques:

### Univariate Analysis

Used to understand the distribution of individual variables.

Examples:

* Trip distance distribution
* Passenger count distribution
* Fare amount distribution

Visualization techniques used:

* Histograms
* Box plots

### Bivariate Analysis

Used to examine relationships between variables.

Examples:

* Trip distance vs fare amount
* Passenger count vs trip distance
* Payment type distribution

Visualization techniques used:

* Scatter plots
* Bar charts
* Box plots

### Multivariate Analysis

Relationships among multiple variables were explored to identify deeper patterns in the dataset.

---

## Key Observations

* Most taxi trips are short-distance rides.
* Passenger counts are generally low, with most trips having one or two passengers.
* Some extreme values exist in trip distance and fare amounts, indicating potential outliers.
* Payment methods vary across trips and reflect passenger preferences.

---

## Project Structure

```
NYC-Taxi-EDA
│
├── EDA_NYC_TAXI_ANALYSES_VANDANA_NEGI.ipynb
├── NYC_TAXI_REPORT_FILE_VANDANA_NEGI.docx
└── README.md
```

---

## How to Run the Project

Clone the repository:

```
git clone https://github.com/yourusername/NYC-Taxi-EDA.git
```

Install required libraries:

```
pip install pandas numpy matplotlib seaborn
```

Run the notebook:

```
jupyter notebook
```

---

## Author

Vandana Negi
Aspiring Data Analyst with interest in data analysis, machine learning, and real-world data problem solving.



These small changes can make your **GitHub look much more professional.**
