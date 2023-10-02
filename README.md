
## Horse Survival Prediction Competition

### Project Overview

This repository hosts the solution for the Horse Survival Prediction competition. The objective of this competition is to predict the outcome of horses based on various features provided in the dataset. The data was generated from a deep learning model trained on a portion of the Horse Survival Dataset. The task involves predicting a categorical target variable called 'outcome'.

### Dataset

The dataset for this competition is provided in two files:

- **train.csv**: This file contains the training data with features and the corresponding outcome labels for a subset of the original Horse Survival Dataset.
  
- **test.csv**: This file contains the test data for which predictions need to be made. The goal is to predict the outcome for these samples.

### Files in the Repository

- **train.csv**: The training dataset used for model training and evaluation.
  
- **test.csv**: The test dataset on which the trained model makes predictions.
  
- **sample_submission.csv**: A sample submission file in the correct format, illustrating how the predictions should be structured for submission.

- **Horse_Survival_Prediction.ipynb**: Jupyter Notebook containing the Python code for data exploration, preprocessing, feature engineering, model training, and evaluation.

### Approach

1. **Data Exploration**: Understanding the structure of the data, exploring feature distributions, and identifying patterns within the dataset.

2. **Data Preprocessing**: Handling missing values, encoding categorical variables, and preparing the data for model training.

3. **Feature Engineering**: Creating new features or transforming existing ones to enhance the model's performance.

4. **Model Selection and Training**: Trying out different machine learning algorithms like XGBoost, LGBM, and CatBoost. Training these models on the preprocessed data.

5. **Evaluation**: Evaluating the models using appropriate metrics (e.g., F1-score) and selecting the best-performing model.

6. **Prediction**: Making predictions on the test dataset using the selected model.

### Instructions to Run the Code

1. Ensure you have Python installed. You can download it from [python.org](https://www.python.org/downloads/).

2. Clone this repository to your local machine using the following command:

   ```
   git clone <repository-url>
   ```

3. Navigate to the cloned repository and install the required Python packages:

   ```
   pip install -r requirements.txt
   ```

4. Open the Jupyter Notebook `Horse_Survival_Prediction.ipynb` using Jupyter Notebook or Jupyter Lab.

5. Execute the cells in the notebook one by one to see the step-by-step process of data exploration, preprocessing, model training, and evaluation.

### Submission

The final predictions are stored in a file named `predictions.csv`. These predictions can be submitted on the competition platform to see the final score.

Feel free to explore the notebook and experiment with different techniques to improve the model's performance. Good luck and happy coding!
