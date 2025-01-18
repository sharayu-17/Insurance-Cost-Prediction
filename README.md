# Insurance Cost Prediction

This project is focused on predicting insurance charges based on demographic and health-related attributes using machine learning techniques. The dataset used for this project includes information about individuals such as age, gender, BMI, smoking habits, and geographical region.
 
 
## Features of the Dataset
The dataset contains 7 columns:
- `age`: Age of the individual.
- `sex`: Gender (`male` or `female`).
- `bmi`: Body Mass Index, a measure of body fat based on height and weight.
- `children`: Number of children/dependents.
- `smoker`: Smoking status (`yes` or `no`).
- `region`: Residential region (`southwest`, `southeast`, `northwest`, `northeast`).
- `charges`: Insurance charges billed.
 
 
## Project Workflow
 
1. **Data Exploration**:
   - Analyze the dataset for structure, missing values, and relationships between features.
   - Visualize the data using libraries like `matplotlib` and `seaborn`.
 
2. **Preprocessing**:
   - Encode categorical variables.
   - Split the dataset into training and test sets.
 
3. **Model Building**:
   - Train a regression model (`LinearRegression`) to predict insurance charges.
   - Evaluate the model using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared.
 
4. **Model Evaluation**:
   - The R-squared value achieved for the model:
     - **Training set**: 0.8316
     - **Testing set**: 0.8249
 
 
