# Gurgoan-house-price-prediction

## Table of Content
-[Project Overview](project-overview)

-[Dataset](dataset)

-[Data Exploration](data-exploration)

-[Model Building](model-building)

-[Model Evaluation](model-evaluation)

-[ Tools](tools)

-[Conclusion](conclusion)

### Project Overview:
The project is about  house prices in Gurgaon, India.
The goal is to predict house prices based on various features using different machine learning models.

### Dataset:
- This dataset contains columns such as property_name, property_type, price, price_per_sqft, area, bedRoom, balcony, and others.
- Data cleaning steps involve removing null values and handling duplicates.
- Outliers in features like balcony, bedRoom, price_per_sqft, and price were treated using interquartile range (IQR) method.

### Aim of the Gurgaon House Price Project
- The primary aim of the Gurgaon House Price dataset is to provide structured information on real estate properties in Gurgaon, 
  helping individuals or organizations understand the housing market. It serves as a foundation for:

- Price Prediction: Estimating property prices based on features like size, location, and amenities.
- Market Trends Analysis: Identifying trends in property values, rental yields, and demand hotspots.
- Decision-Making: Assisting buyers, renters, investors, and developers in making informed decisions.

## Benefits for Individuals
1. Home Buyers
Fair Pricing: Understand price trends across locations to avoid overpaying.
Better Comparisons: Compare properties based on size, location, and amenities.
Targeted Search: Identify areas with affordable properties or those matching their needs.
2. Renters
Rental Insights: Analyze rental prices and choose areas within their budget.
Amenity Awareness: Know what facilities they can expect in different price ranges.
3. Investors
ROI Analysis: Identify high-growth neighborhoods for better investment returns.
Market Trends: Forecast future property values based on past trends.
4. Real Estate Agents/Developers
Market Understanding: Pinpoint customer preferences and optimize their offerings.
Competitive Pricing: Set competitive property prices to attract more buyers.
5. Policymakers
Urban Planning: Use insights to improve infrastructure in underdeveloped areas.
Affordable Housing: Identify regions requiring affordable housing initiatives.


### Data Exploration:
- Statistical analysis showed the distribution of features.
- Correlations between features were determined with a significant correlation between price and bedRoom (0.28), and balcony (0.41).
- Histograms, and correlation heatmaps were used for exploration and visualization.

### Model Building:
- Data was split into training and test sets (80% training, 20% test).
- Linear Regression was initially used but gave a score of 0.52, showing moderate performance.
- K-Nearest Neighbors (KNN) and Support Vector Regression (SVR) models were also tested.
- KNN performed best, with a training score of 0.88 and a test score of 0.72.

### Model Evaluation:
- KNN was selected as the final model due to its superior performance.
- The model had a mean squared error of 2.85 and a root mean squared error of 1.69.
- Cross-validation was performed using 5-fold validation, yielding scores between 0.59 and 0.76.

### Tools
- Tools used: Pandas,Python,Sklearn,Matplotlib, Seaborn

### Conclusion and Benefits:
KNN was the best model for predicting house prices in Gurgaon, with reasonable error and consistency across different training model tested.
This model helps to enhances efficiency by automating the price prediction process, allowing for quicker
responses in fast-paced markets.
This Predictive models contribute to a better understanding of economic conditions through housing trends.
