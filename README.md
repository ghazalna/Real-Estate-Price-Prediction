# Real Estate Price Prediction with Machine Learning

Real Estate Price Prediction is the process of estimating or forecasting the future prices of real estate properties, such as houses, apartments, or commercial buildings. The goal is to provide accurate property rates to buyers, sellers, investors, and real estate professionals to make informed decisions about real estate transactions.

If you want to learn how to predict real estate prices, this project is for you. In this repository, I implement Real Estate Price Prediction with Machine Learning using Python.

## Project Overview

### Process I Follow 

Below is the process we follow for real estate price prediction to help individuals and businesses make informed decisions in the real estate market:

1. **Gather Data:** Collect relevant data from various sources, including real estate databases, government records, online listings, and other public or private sources.

2. **Data Cleaning:** Clean and prepare the collected data by handling missing values, removing outliers, and converting categorical variables into numerical representations.

3. **Feature Engineering:** Create new features or transform existing ones to capture important information that can influence real estate prices.

4. **Exploratory Data Analysis (EDA):** Explore and visualize the data to gain insights into its distribution, correlations, and patterns.

5. **Model Selection:** Choose appropriate machine learning algorithms or predictive models for the task.

6. **Model Training:** Train the selected model on the training data, optimizing its parameters to make accurate predictions.

### Data Insights

For the Real Estate Price Prediction task, we used a dataset with various features that can influence property prices. The dataset analysis revealed insights into the distribution and relationships of different variables:

- **House Age:** Shows a relatively uniform distribution with a slight increase in the number of newer properties.
- **Distance to the Nearest MRT Station:** Most properties are close to an MRT station, but some are quite far.
- **Number of Convenience Stores:** Displays a wide range, suggesting common configurations in terms of convenience store availability.
- **Latitude and Longitude:** Relatively concentrated distributions, indicating properties are located in a geographically limited area.
- **House Price of Unit Area:** Right-skewed distribution with a concentration of properties in the lower price range.

### Model Building

After data exploration, we built a regression model using the Linear Regression algorithm to predict real estate prices. The model's performance was evaluated, and the predictions were visualized.


### Data Histograms

The histograms provide insights into the distribution of each variable:

- **House Age:** Uniform distribution with a slight increase in newer properties.
- **Distance to the Nearest MRT Station:** Most properties are close to an MRT station, with a long tail for farther distances.
- **Number of Convenience Stores:** Wide range with peaks at specific counts (0, 5, 10).
- **Latitude and Longitude:** Relatively concentrated distributions.
- **House Price of Unit Area:** Right-skewed distribution.

### Scatter Plots

The scatter plots explore relationships between variables and house prices:

- **House Age vs. House Price:** No strong linear relationship, but very new and very old houses might have higher prices.
- **Distance to the Nearest MRT Station vs. House Price:** Clear negative trend – as distance increases, house price tends to decrease.
- **Number of Convenience Stores vs. House Price:** Positive relationship – more stores in the vicinity tend to correlate with higher prices.
- **Latitude vs. House Price:** Not a strong linear relationship, but certain latitudes correspond to higher or lower house prices.

### Correlation Analysis

The correlation matrix quantifies relationships between variables and house price:

- **House Age:** Very weak negative correlation (-0.012), age is not a strong predictor.
- **Distance to Nearest MRT Station:** Strong negative correlation (-0.637), closer properties tend to have higher prices.
- **Number of Convenience Stores:** Moderate positive correlation (0.281), more stores positively affect prices.
- **Latitude and Longitude:** Weak correlations with house prices (Latitude: 0.081, Longitude: -0.099).

Overall, proximity to MRT stations and the number of convenience stores seem to be significant factors affecting house prices in this dataset.

### Regression Model

We implemented a regression model using the Linear Regression algorithm to predict real estate prices. The model performance was visualized using scatter plots, showing accurate predictions for a significant portion of the test set.(MAE: 9.518038948836553)


## Conclusion

Real Estate Price Prediction is a valuable application of machine learning, providing insights for buyers, sellers, investors, and professionals in the real estate market. This project demonstrates the process of prediction, key data insights, and the development of a regression model for accurate pricing forecasts.



