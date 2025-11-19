# Analyzing the Iris Dataset with Pandas and Matplotlib

## 📌 Project Overview
This project demonstrates fundamental data analysis skills using **Python**, **Pandas**, and **Matplotlib**.  
The Iris dataset is used to perform data exploration, cleaning, statistical analysis, and visualization.  
The goal is to showcase the ability to understand a dataset, process it, analyze it, and present insights visually.

---

## 📂 Tasks Completed

### **1. Data Loading & Exploration**
- Loaded the Iris dataset using `sklearn.datasets.load_iris()`
- Converted it into a Pandas DataFrame
- Displayed the first few rows with `.head()`
- Checked data types using `.info()`
- Inspected missing values with `.isnull().sum()`
- Iris dataset contains no missing values, so no cleaning was required

---

### **2. Basic Data Analysis**
- Generated statistical summary using `.describe()`
- Computed the mean of all numeric features grouped by species
- Identified key patterns:
  - *Setosa* has the smallest measurements
  - *Virginica* has the largest values across features
  - *Versicolor* lies in between the other two species

---

### **3. Data Visualization**
Four visualizations were created using Matplotlib:

1. **Line Chart**  
   Trend of sepal length across dataset index  

2. **Bar Chart**  
   Average petal length per species  

3. **Histogram**  
   Distribution of sepal length  

4. **Scatter Plot**  
   Relationship between sepal length and petal length  

Each plot includes appropriate titles, axis labels, and formatting.

---

### **4. Findings & Insights**
- Iris species exhibit clear differences in petal and sepal dimensions  
- Petal length and sepal length show a strong positive correlation  
- Sepal length is roughly normally distributed  
- Virginica species consistently have the largest dimensions  
- Setosa species have the smallest dimensions and form a distinct group  

---

## ✔ Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn (optional styling)  
- Scikit-learn (for dataset loading)

---

## 📧 Author
This project was created as part of a Data Analysis learning module.
