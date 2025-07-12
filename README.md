### Video Game Sales Prediction using Linear Regression

This project applies Linear Regression to predict global sales of video games based on historical data. It includes data preprocessing, exploratory data analysis (EDA), model training, and performance evaluation.

## Objective

To predict video game global sales using machine learning techniques, with a focus on understanding how features like genre, platform, and year influence sales.

## Dataset
Name: Video Game Sales Dataset
Source: Kaggle - Video Game Sales (https://www.kaggle.com/datasets/gregorut/videogame-sales-with-ratings)

Features:
Name, Platform, Year, Genre, Publisher,NA_Sales, EU_Sales, JP_Sales, Other_Sales, Global_Sales

## Technologies & Libraries
- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn

## Project Workflow
1. **Data Cleaning**
   - Handle missing values
   - Convert data types
   - Remove irrelevant columns
2. **Exploratory Data Analysis (EDA)**
   - Sales trends over years
   - Genre-wise and platform-wise distributions
   - Correlation heatmap
3. **Feature Engineering**
   - Encoding categorical variables
   - Selecting relevant features
4. **Modeling**
   - Split data into training and test sets
   - Apply Linear Regression
   - Evaluate using R², MAE, MSE
5. **Visualization**
   - Actual vs Predicted Sales
   - Residual plots

## Results
- Achieved an R² score of approximately `XX` (fill in based on your results)
- Found `Platform` and `Year` as key predictors
- Model is a baseline and can be improved with more features or advanced regressors


## How to Run
1. Clone the repository:
git clone https://github.com/your-username/video-game-sales-prediction.git
cd video-game-sales-prediction
2. Install dependencies:
pip install -r requirements.txt
3. Open the notebook:
jupyter notebook video_game_sales.ipynb
