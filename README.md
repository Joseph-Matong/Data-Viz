# Data-Viz
Iris Dataset Analysis and Visualization 🏵️📊

This project explores the classic **Iris dataset**, a foundational dataset in machine learning and data analysis. The analysis focuses on understanding the dataset through descriptive statistics and visualizations, leveraging Python libraries such as `pandas`, `matplotlib`, and `seaborn`.

---

## **Objective**

- To load and explore the Iris dataset using the `pandas` library.
- To perform basic data analysis and compute meaningful statistics.
- To create informative visualizations for better data understanding.
- To identify patterns and trends within the dataset.

---

## **Tasks**

### **Task 1: Load and Explore the Dataset**
1. Load the Iris dataset using `pandas`.
   - The Iris dataset is provided by the `sklearn.datasets` module and can also be downloaded in CSV format.
2. Display the first few rows of the dataset to inspect its structure.
3. Check the data types and identify any missing values.
4. Clean the dataset (if necessary) by handling missing data.

---

### **Task 2: Basic Data Analysis**
1. Compute descriptive statistics using `.describe()` to understand key metrics for numerical columns.
2. Group the data by `species` and compute the average for numerical features:
   - Sepal Length
   - Sepal Width
   - Petal Length
   - Petal Width
3. Identify any patterns or differences between species.

---

### **Task 3: Data Visualization**
Create four different types of visualizations to uncover insights:

1. **Line Chart**  
   - Plot the trend of a specific feature, such as petal length, for all species.

2. **Bar Chart**  
   - Compare average sepal width for each species.

3. **Histogram**  
   - Visualize the distribution of petal length to identify its spread and central tendency.

4. **Scatter Plot**  
   - Show the relationship between petal length and petal width, color-coded by species.

---

## **Dataset Information**

The **Iris dataset** contains measurements of iris flowers from three species:
- *Setosa*
- *Versicolor*
- *Virginica*

### Features:
- **Sepal Length (cm)**: Length of the sepal.
- **Sepal Width (cm)**: Width of the sepal.
- **Petal Length (cm)**: Length of the petal.
- **Petal Width (cm)**: Width of the petal.
- **Species**: The class label indicating the species of the flower.
