# WALK-RUN
# 🚶‍♂️🏃‍♀️ Walk vs. Run Classification

## 📌 Project Overview
This machine learning project focuses on Human Activity Recognition (HAR). The goal is to build a classification model capable of accurately predicting whether a person is walking or running based on biometric sensor data. 

As wearable technology becomes more prevalent, models like this are essential for fitness tracking applications, health monitoring, and sports analytics.

## 🗂️ Dataset Information
The dataset contains sequential data collected from mobile sensors (typically accelerometers and gyroscopes) while users were either walking or running.
* **Key Features:**
  * `acceleration_x`, `acceleration_y`, `acceleration_z`
  * `gyro_x`, `gyro_y`, `gyro_z`
  * Time steps or date features
* **Target Variable:** `Activity` (0 for Walk, 1 for Run)

## 🛠️ Tech Stack & Tools
* **Programming Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn
* **Environment:** Jupyter Notebook (`WALK_RUN.ipynb`)

## ⚙️ Project Workflow
1. **Data Loading & Cleaning:** * Handling missing values and ensuring continuous time-series data is properly formatted.
2. **Exploratory Data Analysis (EDA):** * Plotting sensor distributions to visually differentiate the intensity of walking vs. running.
   * Correlation heatmaps to check for multicollinearity among sensor axes.
3. **Data Preprocessing:** * Feature scaling (StandardScaler/MinMaxScaler) to ensure all sensor readings are on the same scale.
   * Encoding the categorical target variable.
4. **Model Building:** * Training various classification algorithms (e.g., Logistic Regression, Support Vector Machines, Random Forest).
5. **Model Evaluation:** * Assessing performance using Accuracy, Precision, Recall, F1-Score, and a Confusion Matrix.

## 🚀 How to Run the Project
1. **Clone this repository:**
   ```bash
   git clone [https://github.com/VISHNUREDDY352/Walk-Run-Classification.git](https://github.com/VISHNUREDDY352/Walk-Run-Classification.git)
