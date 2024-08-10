# Red Wine Quality Prediction

This project analyzes the quality of red variants of the Portuguese “Vinho Verde” wine using various physicochemical tests as input variables.

## Dataset

The dataset used in this project contains the following input variables based on physicochemical tests:

- Fixed acidity
- Volatile acidity
- Citric acid
- Residual sugar
- Chlorides
- Free sulfur dioxide
- Total sulfur dioxide
- Density
- pH
- Sulphates
- Alcohol

The output variable is the **quality** of the wine, scored between 3 and 8, based on sensory data.

## Project Structure

1. **Data Import:**
   - The dataset is loaded and explored for initial insights.
2. **Missing Data:**
   - No missing data is found in the dataset.
3. **Imbalance Check:**
   - The dataset is identified to have an imbalance in the target variable.
4. **Principal Component Analysis (PCA):**
   - The features are reduced to 8 principal components, explaining approximately 96% of the total variance.
5. **Train-Test Split:**
   - The dataset is split into training and testing sets for model evaluation.
6. **Modeling**

## Dependencies

The project requires the following Python libraries:

- pandas
- matplotlib
- seaborn
- scikit-learn
