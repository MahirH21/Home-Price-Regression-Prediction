# Home-Price-Regression-Prediction
## Data Source
- **Housing Price Prediction Data** ([Kaggle link](https://www.kaggle.com/datasets/muhammadbinimran/housing-price-prediction-data?select=housing_price_dataset.csv))

### Goal
Develop a machine learning model to predict housing prices based on features such as square footage, number of bedrooms, bathrooms, neighborhood, and year built. The project aims to help potential home buyers and real estate professionals make data-driven decisions.

### Summary
- Collected housing price data.
- Preprocessed data by:
  - Handling missing values.
  - Performing one-hot encoding for categorical variables.
- Built a **linear regression model** to predict home prices.
- Created data visualizations:
  - Correlation matrix.
  - Scatter plots.
  - Box plots.
- Evaluated the model using the following metrics:
  - **R²**
  - **Mean Absolute Error (MAE)**
  - **Mean Squared Error (MSE)**
  - **Root Mean Squared Error (RMSE)**

### Results
- The model explains **56%** of the variance in home prices.
- **RMSE**: Approximately **$50,172**, with evenly distributed prediction errors.

### Tech Stack
- **Language**: Python
- **Libraries**: Pandas, Matplotlib, Seaborn, Scikit-learn, NumPy
- **Tool**: Google Colab
