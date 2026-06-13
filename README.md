

# Crop Recommendation Machine Learning Project

## Project Overview

This project builds a machine learning model to recommend the most suitable crop based on soil and environmental conditions. The purpose of the project is to show how data science and machine learning can support food security by helping farmers make better crop selection decisions.

The model uses soil nutrients and climate-related features to predict the best crop type. By matching crops with appropriate growing conditions, farmers may be able to improve productivity, reduce waste, and lower the risk of crop failure.

## Study Theme

The study theme of this project is using data science and machine learning to improve food security and reduce hunger by making agriculture more efficient, fair, and sustainable.

This project connects to the theme because crop recommendation can help farmers choose crops that are more suitable for their soil and climate conditions. Better crop planning can support higher yield, better resource use, and more sustainable agricultural decision-making.

## Dataset

The dataset used in this project is the **Crop Recommendation Dataset** from Kaggle.

Dataset link: https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset

The dataset contains soil and environmental features that are useful for crop recommendation.

### Features

The input features include:

- `N`: Nitrogen content in the soil
- `P`: Phosphorus content in the soil
- `K`: Potassium content in the soil
- `temperature`: Temperature in degrees Celsius
- `humidity`: Humidity percentage
- `ph`: Soil pH value
- `rainfall`: Rainfall amount

### Target Variable

- `label`: Recommended crop type

## Project Objective

The objective of this project is to build a supervised machine learning classification model that predicts the most suitable crop based on soil and climate conditions.

The project compares several classification algorithms and selects the best-performing model based on evaluation metrics.

## Machine Learning Process

The project follows the main steps of a standard machine learning workflow:

1. Load the dataset
2. Explore the data
3. Check data quality
4. Clean the data
5. Select features and target variable
6. Split the dataset into training and testing sets
7. Train multiple machine learning models
8. Tune model parameters
9. Evaluate model performance
10. Select the final model
11. Interpret the results

## Models Used

The following supervised learning models are compared:

- Decision Tree Classifier
- Random Forest Classifier
- K-Nearest Neighbors Classifier
- Support Vector Machine Classifier

Random Forest is selected as the final model because it performs well on structured tabular data and provides feature importance, which helps explain which factors are most useful for crop prediction.

## Evaluation Metrics

The models are evaluated using the following classification metrics:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrix

These metrics help compare how well each model predicts the correct crop category.

## Files Included

The project includes the following files:

- `Crop_Recommendation_Project_Code.py`: Full Python code for data loading, cleaning, visualization, model training, tuning, and evaluation
- `Crop_Recommendation_Project_Report.pdf`: Final project report
- `Crop_Recommendation_Project_Presentation.pptx`: PowerPoint presentation
- `crop_project_outputs/`: Folder containing generated charts and model results

## Required Python Libraries

To run the project, install the following Python libraries:

```bash
pip install pandas numpy matplotlib scikit-learn
```

## How to Run the Project

1. Download the Crop Recommendation Dataset from Kaggle.
2. Place the dataset file named `Crop_recommendation.csv` in the same folder as the Python script.
3. Run the Python script:

```bash
python Crop_Recommendation_Project_Code.py
```

4. The script will generate model results, charts, and output files in the `crop_project_outputs` folder.

## Output Files

After running the script, the following outputs will be created:

- `class_distribution.png`
- `correlation_heatmap.png`
- `model_accuracy.png`
- `confusion_matrix.png`
- `feature_importance.png`
- `model_results.csv`
- `feature_importance.csv`
- `project_summary.txt`

## Example Prediction

The final trained model can take soil and climate values as input and predict a recommended crop. For example, the model can use values for nitrogen, phosphorus, potassium, temperature, humidity, pH, and rainfall to recommend a suitable crop.

## Conclusion

This project shows how machine learning can be used to support agricultural decision-making. A crop recommendation model can help farmers select crops that match their soil and climate conditions. This can improve resource efficiency, increase crop productivity, and support the broader goal of improving food security and reducing hunger.

## Author

Bokun Ge
