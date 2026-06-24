# Travel Cost Classification Project

## Project Overview
This project uses machine learning classification to predict travel cost categories based on trip information. The goal is to classify trips into three categories:

- Low Cost
- Medium Cost
- High Cost

The dataset includes travel-related details such as destination, trip duration, traveler demographics, accommodation costs, and transportation costs.

This project was completed as part of Assignment 8 for Supervised Learning Classification.

---

## Dataset Information
The dataset used in this project is:

**Travel details dataset.csv**

It contains the following features:

- Trip ID
- Destination
- Start date
- End date
- Duration (days)
- Traveler name
- Traveler age
- Traveler gender
- Traveler nationality
- Accommodation type
- Accommodation cost
- Transportation type
- Transportation cost

---

## Project Steps

The notebook follows these steps:

### 1. Data Loading
- Import dataset into Google Colab
- Check dataset shape and column names

### 2. Data Preprocessing
- Remove duplicates
- Handle missing values
- Convert cost columns into numeric format
- Encode categorical data
- Create new features:
  - Total_Cost
  - Start_Month
  - Trip_Length
- Create target variable:
  - Cost_Category

### 3. Exploratory Data Analysis (EDA)
- Cost category distribution bar chart
- Correlation heatmap

### 4. Model Building
The following models were trained:

- Logistic Regression
- Random Forest Classifier
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)

### 5. Model Evaluation
Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

---

## Installation and Setup

To run this project, install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## How to Run the Notebook

### Option 1: Google Colab
1. Open the notebook in Google Colab
2. Upload the dataset file:
   `Travel details dataset.csv`
3. Run all cells from top to bottom

### Option 2: Jupyter Notebook
1. Clone the repository:

```bash
git clone <your-repository-link>
```

2. Open the project folder:

```bash
cd travel-classification-project
```

3. Launch Jupyter Notebook:

```bash
jupyter notebook
```

4. Open the notebook file and run all cells

---

## Files Included

- `Lesson_8_Assignment_AI.ipynb` → Main notebook
- `Travel details dataset.csv` → Dataset
- `Report.pdf` → Final report
- `README.md` → Project documentation

---

## Results
After testing all models, Random Forest performed the best and gave the highest accuracy.

This project helped demonstrate:

- Data cleaning
- Feature engineering
- Classification modeling
- Model evaluation
- Deployment planning

---

## Author

**Alyssa Iapalucci**
