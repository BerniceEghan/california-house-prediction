# california-house-prediction
#  House Price Prediction - California Housing Dataset

##  Project Overview

This project implements a comprehensive machine learning pipeline for predicting house prices in California using the classic California Housing Dataset.

##  Business Problem

Predicting median house values in California districts based on various demographic, geographic, and housing characteristics. 

### Core Libraries and Tools:
- **pandas** & **numpy**: Data manipulation and numerical computations
- **scikit-learn**: Machine learning models and preprocessing
- **matplotlib** & **seaborn**: Data visualization
- **xgboost**: Gradient boosting implementation
- **Streamlit**: Web application framework 
- **SHAP**: Model interpretability and feature importance

##  Project Structure

### 1. Data Loading & Initial Exploration
- Load California Housing Dataset
- Basic dataset statistics and information
- Data quality checks (missing values, duplicates)

### 2. Exploratory Data Analysis (EDA)
- **Distribution Analysis**: Histograms for all features
- **Correlation Analysis**: Heatmap of feature relationships
- **Geographic Visualization**: California map with price distribution
- **Feature Relationships**: Scatter plots with trend lines
- **Outlier Detection**: Boxplots and statistical analysis

### 3. Key Insights from EDA

#### Strong Correlations:
- **MedInc** vs House Price: Strong positive correlation (0.69)
- **HouseAge** vs House Price: Moderate positive correlation
- Geographic patterns clearly visible in coastal vs inland areas

#### Data Quality:
-  No missing values
-  No duplicate rows
-  Consistent data types 

##  Model Development

### Preprocessing:
- Train-test split (80-20%)
- Feature scaling using StandardScaler
- Handling of outliers and skewed distributions

### Planned Models:
1. **Linear Regression** (Baseline)
2. **Random Forest**
3. **Gradient Boosting (XGBoost)**
4. **Ensemble Methods**

### Evaluation Metrics:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R-squared Score
- Cross-validation scores

##  Visualization Highlights

### 1. Geographic Distribution
- Interactive California map colored by house prices
- Clear coastal premium patterns
- Urban vs rural price differences

### 2. Feature Relationships
- Income vs Price: Strong linear relationship
- Location-based clustering evident
- Room/bedroom ratios and occupancy insights

### 3. Correlation Patterns
- Income shows strongest correlation with prices
- Geographic coordinates show meaningful spatial patterns

##  Future Enhancements

-  Implement all planned machine learning models
-  Implement time-series analysis for price trends
-  Real-time prediction capabilities

