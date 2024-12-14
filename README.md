# Mielage Prediction

## Project Overview
This project focuses on predicting the mileage of vehicles using regression analysis. By analyzing vehicle-related data, the aim is to develop a regression model capable of accurate predictions.

## Objective
To predict the mileage (MPG - Miles Per Gallon) of vehicles based on various features using regression techniques.

## Dataset
The dataset used in this project is sourced from the [YBI Foundation GitHub Repository](https://github.com/YBI-Foundation/Dataset/raw/main/MPG.csv).

### Features
- The dataset contains multiple features related to vehicle specifications and performance.

### Target Variable
- **Miles Per Gallon (MPG)**: The target variable represents the mileage of a vehicle.

## Tools and Libraries
The following tools and Python libraries are utilized in this project:
- **pandas**: For data loading, manipulation, and preprocessing.
- **matplotlib** and **seaborn**: For data visualization and exploratory data analysis.
- **scikit-learn**: For regression modeling and evaluation metrics.

## Steps Included
1. **Data Import**: Load the dataset into a Pandas DataFrame.
2. **Data Preprocessing**: Clean the data, handle missing values, and prepare features for model training.
3. **Exploratory Data Analysis**: Visualize relationships between features and the target variable.
4. **Model Building**: Train a Linear Regression model to predict the MPG of vehicles.
5. **Evaluation**: Evaluate the model using metrics such as Mean Absolute Percentage Error (MAPE).

## Getting Started
To replicate this project, follow the steps below:

1. Clone the repository:
    ```bash
    git clone https://github.com/SrishtiTurki/Mileage-Prediction.git
    ```
2. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the Jupyter Notebook:
    ```bash
    jupyter notebook Mielage_Prediction.ipynb
    ```

## Results
- The Linear Regression model effectively predicts vehicle mileage.
- Insights from the exploratory analysis are visually represented in the notebook.

## Repository Structure
```
.
├── Mielage_Prediction.ipynb        # Jupyter Notebook containing the project code
├── requirements.txt               # Required Python libraries
└── README.md                      # Project documentation
```
