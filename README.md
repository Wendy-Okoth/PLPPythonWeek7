# 📊 Data Analysis & Visualization Assignment

## 🎯 Objective
The purpose of this assignment is to:
- Load and analyze a dataset using **pandas** in Python  
- Perform basic data exploration and statistical analysis  
- Create visualizations using **matplotlib** and **seaborn**  
- Document findings and observations  

---

## 📂 Files Included
- `DataAnalysis.ipynb` → Jupyter Notebook version with step-by-step tasks, explanations, and visualizations  
- `README.md` → This documentation file  

---

## 📊 Dataset
We are using the **Iris Dataset**, a classic dataset from scikit-learn.  
- 150 samples of iris flowers  
- 4 features: sepal length, sepal width, petal length, petal width  
- 3 species: Setosa, Versicolor, Virginica  

---

## ✅ Tasks
1. **Load & Explore Dataset**
   - Display first few rows with `.head()`
   - Check dataset structure with `.info()`
   - Handle missing values (if any)

2. **Basic Data Analysis**
   - Compute summary statistics with `.describe()`
   - Group data by species and compute mean values
   - Identify insights and trends

3. **Data Visualization**
   - Line chart of measurements across samples
   - Bar chart of average values per species
   - Histogram of numerical feature distribution
   - Scatter plot to visualize relationships between features

---

## 📈 Sample Visualizations
- Line Chart → Sepal vs Petal Length over samples  
- Bar Chart → Average Petal Length by species  
- Histogram → Sepal Length distribution  
- Scatter Plot → Sepal Length vs Petal Length by species  

---

## ⚙️ Requirements
- Python 3.8+
- Jupyter Notebook (if using `.ipynb`)
- Libraries:
  - pandas  
  - matplotlib  
  - seaborn  
  - scikit-learn  

Install them with:
```bash
pip install pandas matplotlib seaborn scikit-learn
▶️ How to Run
Option 1: Google Colab (Recommended)
Open Google Colab

Upload DataAnalysis.ipynb

Run cells one by one

Option 2: Local Jupyter Notebook
bash
Copy code
jupyter notebook DataAnalysis.ipynb

📌 Findings
Iris dataset is clean with no missing values.

Setosa species is clearly separable due to small petal size.

Versicolor and Virginica overlap, but Virginica tends to have larger petals.

Petal features are more discriminative than sepal features.
