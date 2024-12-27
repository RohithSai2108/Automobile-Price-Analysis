# Automobile-Price-Analysis

## Overview
This project involves a detailed exploratory data analysis (EDA) of the Automoblie Dataset dataset to uncover insights about the automotive market, including trends in pricing, vehicle specifications, and fuel types. The analysis uses Python libraries like `pandas`, `matplotlib`, and `seaborn` to process and visualize the data, aiming to provide actionable insights for stakeholders.

---

## Objectives
1. **Understand the Dataset:** Analyze the range of manufacturing years, pricing, and other attributes.
2. **Identify Trends:** Explore relationships between price, mileage, engine power, and other features.
3. **Handle Data Issues:** Manage missing values, outliers, and inconsistent entries.
4. **Generate Insights:** Provide visualizations and statistical insights to summarize the data.

---

## Dataset
The dataset contains the following features:
- **Name:** The name of the car.
- **Year:** Year of manufacturing.
- **Selling_Price:** Price at which the car is sold.
- **Present_Price:** Current price of the car.
- **Kms_Driven:** Distance covered by the vehicle in kilometers.
- **Fuel_Type:** Type of fuel used (Petrol/Diesel/Other).
- **Seller_Type:** Type of seller (Dealer/Individual).
- **Transmission:** Transmission type (Manual/Automatic).
- **Owner:** Number of previous owners.

---

## Analysis Steps
### 1. Data Loading and Cleaning
- Load the dataset using `pandas`.
- Handle missing values by imputation or removal.
- Remove duplicate entries and handle inconsistent data.

### 2. Exploratory Data Analysis (EDA)
#### Summary Statistics
- Compute basic statistics (mean, median, mode, etc.).
- Analyze skewness and kurtosis for numerical columns.

#### Visualizations
- Distribution of selling prices.
- Relationships between mileage, engine size, and price.
- Bar charts for categorical features like `Fuel_Type` and `Seller_Type`.
- Correlation heatmap to identify feature relationships.

### 3. Outlier Detection and Removal
- Use box plots to detect outliers in numerical features like price and mileage.
- Apply IQR methods to remove extreme outliers.

### 4. Advanced Analysis
- Hypothesis testing to compare price distributions across fuel types.
- Feature importance analysis using Random Forest.

### 5. Optional Predictive Modeling
- Use linear regression to predict car prices based on key features.
- Evaluate model performance using metrics like RMSE and R^2.

---

## Tools and Libraries
- **Data Manipulation:** `pandas`, `numpy`
- **Visualization:** `matplotlib`, `seaborn`, `plotly`
- **Statistical Analysis:** `scipy`
- **Machine Learning (Optional):** `scikit-learn`

---

## Key Insights
- **Price Trends:** Older vehicles generally have lower selling prices.
- **Fuel Type:** Diesel vehicles dominate higher price ranges.
- **Mileage vs Price:** Higher mileage tends to correspond to lower prices.

---

## Results
- Detailed statistical summaries and visualizations.
- Identification of key trends and actionable insights.
- Predictive model showcasing the impact of various features on selling price.

---

## How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/RohithSai2108/Automobile-Price-Analysis.git
   ```
2. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook Automoblie_Price_PROJECT_ANALYSIS.ipynb
   ```

---

## Future Work
- Extend the analysis to include geographical data visualization.
- Integrate advanced machine learning models for price prediction.
- Explore real-time datasets for broader market trends.

---

## Author
Rohith

---

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.
