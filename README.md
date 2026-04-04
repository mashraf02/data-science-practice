# data-science-practice
# Python Data Science Practice

This repository contains my beginner-level Jupyter notebooks for learning core Python libraries used in **Data Science** and **Data Analysis**:

- **NumPy**
- **Pandas**
- **Matplotlib**
- **Seaborn**

I practiced these using the **Iris dataset** and custom sample data.

## 📁 Repository Structure
python-data-science-practice/
├── data/
│   └── irisdata.csv                 ← Iris dataset used in NumPy, Pandas, Matplotlib & Seaborn
├── numPy_tutorial.ipynb
├── pandas_tutorial.ipynb
├── matplotlib_tutorial.ipynb
├── seaborn_tutorial.ipynb
└── README.md


## 📘 Notebooks & Topics Covered

### 1. `numPy_tutorial.ipynb` - NumPy Basics
- Understanding rows (samples) vs columns (features)
- Creating NumPy arrays (`np.array`, `np.random.rand`, `np.random.randint`)
- Array attributes: `shape`, `ndim`, `size`, `dtype`
- Indexing and slicing (rows, columns, specific elements)
- Dataset splitting into features (`X`) and labels (`y`)
- Manual train-test split
- Handling missing values (`np.nan`, `np.isnan`, `np.nanmean`)
- Statistical operations: `mean`, `std`, `min`, `max`
- Normalization and Standardization

### 2. `pandas_tutorial.ipynb` - Pandas for Data Manipulation
- Reading CSV files (`pd.read_csv`)
- Basic exploration: `head()`, `tail()`, `shape`, `info()`, `describe()`, `columns`
- Column renaming
- Indexing & selection: `iloc[]`, `loc[]`
- Boolean filtering and conditional selection
- Basic data analysis on the Iris dataset

### 3. `matplotlib_tutorial.ipynb` - Data Visualization with Matplotlib
- Loading and preparing data with Pandas
- Renaming columns for easier use
- Creating histograms
- Visualizing distribution of features (e.g., Petal Length) by class
- Customizing plots (labels, title, legend, alpha)

### 4. `seaborn_tutorial.ipynb` - Statistical Visualization with Seaborn
- Introduction to Seaborn and its integration with Pandas
- Setting plot style (`sns.set_style`)
- Creating scatter plots with hue (color by class)
- Beautiful statistical visualizations (Sepal Length vs Sepal Width by species)
- Enhancing Matplotlib plots with Seaborn

## 🛠 Technologies Used

- **Python**
- **Jupyter Notebook**
- **NumPy** — Numerical computing
- **Pandas** — Data manipulation & analysis
- **Matplotlib** — Basic plotting
- **Seaborn** — Statistical data visualization

## 🚀 How to Run the Notebooks

1. Clone the repository:
   ```bash
   git clone https://github.com/mashraf02/data-science-practice.git
   cd data-science-practice
