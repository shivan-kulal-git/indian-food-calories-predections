# Indian Food Calories Predictions

## Overview
This project implements a diet recommendation system based on the Indian Recommended Dietary Allowance (RDA) using machine learning techniques. The primary objective is to predict the caloric content of various food items based on their nutritional values and provide users with a simple GUI to find calorie information.

## Technologies Used
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Statsmodels
- Scikit-learn
- XGBoost
- Tkinter

## Dataset
The dataset used for this project is `indian_rda_based_diet_recommendation_system.csv`. It contains nutritional information for various food items, including:
- Fats
- Proteins
- Iron
- Calcium
- Sodium
- Potassium
- Carbohydrates
- Fibre
- Sugars
- Calories

## Installation
1. Clone the repository:
   ```
   git clone https://github.com/your_username/your_repository.git
   cd your_repository
   ```

2. Install the required libraries:
   ```
   pip install -r requirements.txt
   ```

## Usage
1. **Model Training and Evaluation**
   - The Jupyter notebook provided contains the complete workflow for data preprocessing, model training, hyperparameter tuning, and evaluation.
   - Run the notebook cells sequentially to train the model and visualize the results.

2. **Calorie Finder GUI**
   - To run the GUI application, execute the following command:
     ```
     python gui_calorie_finder.py
     ```
   - Enter the name of a food item in the input box to find its caloric content.

## Key Features
- Data preprocessing including handling missing values and normalization.
- Implementation of the XGBoost regression model with hyperparameter tuning.
- Evaluation of the model using various metrics (MSE, R², MAE, EVS).
- User-friendly GUI for quick calorie lookups.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any enhancements or bug fixes.

## Acknowledgments
- XGBoost
- Scikit-learn
- Tkinter

--- 
