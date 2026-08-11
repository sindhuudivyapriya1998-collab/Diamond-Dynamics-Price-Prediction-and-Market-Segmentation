# Diamond-Dynamics-Price-Prediction-and-Market-Segmentation
The Diamond price prediction &amp; market segmentation project uses machine learning to analyze diamond characteristics, predict diamond prices, and identify meaningful market segments. The project includes both supervised learning and unsupervised learning for customer or diamond segmentation.

# Objectives
1. Analyze the factors that influence diamond prices.
2. Preprocess numerical and categorical diamond features.
3. Create meaningful features for machine learning.
4. Build and compare different price prediction models.
5. Identify meaningful diamond segments using K-Means clustering.
6. Deploy the prediction and clustering models using Streamlit

# Technologies used:
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow/Keras
- XGBoost
- Joblib
- Streamlit

# Project workflow
  # 1.Data collection
   The diamond dataset was loaded and inspected for structure, data types, missing values and duplicate records.
  # 2.Data preprocessing
   - Handling missing values
   - Handling duplicates
   - Detecting outliers
   - Data type conversion
   - Numerical feature analysis
   - Categorical feature analysis
  # 3.Exploratory Data Analysis
   The relationship between diamond characteristics and price was analyzed using
   - Histograms
   - Box plots
   - Bar plots
   - Scatter plots
   - Correlation analysis
   - Heatmap
  # 4.Feature Engineering
   A new feature called carat_category was created to categories diamonds into
   - Light
   - Medium
   - Heavy
  # 5.Models Explored
   - Linear regression
   - Random forest
   - K-Nearest Neighbors
   - XGBoost
   - Decision Tree
   - Artificial Neural Network(ANN)
  # 6.XGBoost Model
  XGBoost was selected as the final model for diamond price prediction after comparing multiple regression models.
  It was chosen because it provides good prediction performance and effectively captures the non-linear relationship between diamond features and price.

  # 7.Clustering & Market segmentation
   K-Means clustering was used to identify groups of diamonds with similar characteristics. Elbow method was used to determine a suitable number od clusters.

# Streamlit Application
  A streamlit application was developed with two main modules.

  # Price prediction
  The model predicts diamond prices using features such as:
   - carat
   - cut
   - color
   - clarity
   - X,Y,Z dimensions
  # Clustering/Market segmentation
  The application also provides clustering insights and allows users to understand which market segment a diamond belongs to.

   
    
