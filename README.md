# Concert Revenue Prediction

## Project Overview
This project predicts concert revenue based on various features such as the artist, tour title, number of shows, and average gross revenue. The goal is to use machine learning models to estimate **Actual Gross Revenue** for concert tours.

## Features
- **Artist**: Name of the performing artist.
- **Tour Title**: The title of the concert tour.
- **Shows**: Number of shows during the tour.
- **Average Gross**: The average revenue per show.
- **Actual Gross**: The actual gross revenue (target variable).

## Steps Involved
1. **Data Collection & Preprocessing**:
   - Loaded and cleaned the dataset.
   - Handled missing values and outliers.
   - Encoded categorical variables like artist and tour title.

2. **Exploratory Data Analysis (EDA)**:
   - Performed visualizations to explore relationships and patterns in the data.
   - Identified correlations between features.

3. **Modeling**:
   - Trained and tested multiple machine learning models including:
     - **Linear Regression**
     - **Random Forest**
   - Evaluated model performance using metrics like MAE and R-squared.

4. **Visualization**:
   - Plotted feature importances to understand the impact of each feature on the prediction.

## Requirements
- Python 3.x
- Libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn

## How to Run
1. Clone the repository.
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the `main.py` script to start the analysis and model training.

## Conclusion
This project demonstrates the use of machine learning for predicting concert revenue based on historical data. The Random Forest model achieved the best performance in predicting the target variable.

---

You can adjust and expand this README based on any additional features or specific instructions you want to include in your GitHub repository.
