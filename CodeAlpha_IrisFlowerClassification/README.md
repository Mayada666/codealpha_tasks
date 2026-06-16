# 🌸 Iris Flower Classification using Machine Learning

## 📌 Project Overview

This project is part of the CodeAlpha Machine Learning Internship.

The objective is to build a machine learning model capable of classifying Iris flowers into one of three species based on their physical measurements:

* Iris-setosa
* Iris-versicolor
* Iris-virginica

The classification is performed using supervised machine learning algorithms implemented with Scikit-learn.

---

## 🎯 Project Objectives

* Perform data exploration and cleaning.
* Analyze relationships between flower features.
* Visualize data using multiple plots.
* Train machine learning classification models.
* Compare model performance.
* Evaluate accuracy using different metrics.
* Predict flower species from new user-provided measurements.

---

## 📊 Dataset Information

The Iris dataset contains four numerical features:

| Feature       | Description              |
| ------------- | ------------------------ |
| SepalLengthCm | Length of the sepal (cm) |
| SepalWidthCm  | Width of the sepal (cm)  |
| PetalLengthCm | Length of the petal (cm) |
| PetalWidthCm  | Width of the petal (cm)  |

Target Variable:

* Iris-setosa
* Iris-versicolor
* Iris-virginica

Dataset Size:

* Original Samples: 150
* Features: 4
* Classes: 3

---

## 🔍 Exploratory Data Analysis (EDA)

Several visualizations were used to understand the dataset:

### Pair Plot

Used to observe relationships between all feature pairs and identify class separation.

### Correlation Heatmap

Used to analyze feature correlations and identify the most informative features.

### Box Plots

Used to examine:

* Feature distributions
* Median values
* Spread of data
* Potential outliers
* Species separation

### Key Insights

* Petal Length and Petal Width are the most important features.
* Iris-setosa is clearly separated from the other species.
* Iris-versicolor and Iris-virginica show slight overlap.
* Sepal Width has the lowest discriminative power.

---

## ⚙️ Data Preprocessing

The following preprocessing steps were applied:

* Removed the unnecessary ID column.
* Checked for missing values.
* Removed duplicate records.
* Encoded species labels into numerical values.
* Split data into training and testing sets.
* Standardized feature values using StandardScaler.

---

## 🤖 Machine Learning Models

The following classification algorithms were trained and evaluated:

### K-Nearest Neighbors (KNN)

Main classification model used in the project.

### Logistic Regression

Linear classification baseline.

### Decision Tree Classifier

Tree-based classification model.

---

## 📈 Model Evaluation

Evaluation techniques used:

* Accuracy Score
* Confusion Matrix
* Classification Report
* Cross Validation

Example Results:

| Model               | Accuracy |
| ------------------- | -------- |
| KNN                 | 93.33%   |
| Logistic Regression | 93.33%   |
| Decision Tree       | 93.33%   |

Cross-Validation Mean Accuracy:

96.6%

---

## 🏆 Best Findings

* Petal measurements are the strongest predictors of species.
* Iris-setosa can be classified almost perfectly.
* The main classification challenge is distinguishing Iris-versicolor from Iris-virginica.
* Cross-validation confirms that the model generalizes well to unseen data.

---

## 🌸 User Prediction Feature

The project includes an interactive prediction system where users can enter:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

The trained model then predicts the flower species and displays the result.

Example:

Input:

Sepal Length = 5.1
Sepal Width = 3.5
Petal Length = 1.4
Petal Width = 0.2

Output:

Predicted Flower Type:
Iris-setosa

---

## 🛠 Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab

---

## 📂 Project Structure

CodeAlpha_IrisFlowerClassification/

├── data/

├── notebooks/

├── images/

├── README.md


---

## 🚀 How to Run

1. Clone the repository.

2. Open the notebook or Python script.

3. Run all cells.

4. Upload the Iris dataset when prompted.

5. View visualizations, evaluation results, and make predictions.

---

## 📚 Learning Outcomes

Through this project, I learned:

* Data preprocessing techniques
* Exploratory Data Analysis (EDA)
* Feature importance analysis
* Classification algorithms
* Model evaluation methods
* Cross-validation
* Building end-to-end machine learning pipelines

---

## 👩‍💻 Author

Mayada Abou Hamdan

CodeAlpha Machine Learning Intern
