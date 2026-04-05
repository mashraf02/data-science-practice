# Python Data Science Practice

This repository contains my beginner practice Jupyter notebooks for core Python Data Science libraries: **NumPy, Pandas, Matplotlib, and Seaborn**.

I practiced these using the Iris dataset and custom sample data.

## 📁 Repository Structure
data-science-practice/
├── data/
│   └── irisdata.csv                    ← Iris dataset used in the notebooks
├── numPy_tutorial.ipynb
├── pandas_tutorial.ipynb
├── matplotlib_tutorial.ipynb
├── seaborn_tutorial.ipynb
├── Valentine_spending.ipynb
└── README.md


## 📘 Notebooks & Topics Covered

### 1. `numPy_tutorial.ipynb` - NumPy Basics
- Creating arrays (`np.array`, `np.random.rand`, `np.random.randint`)
- Array attributes: `shape`, `ndim`, `size`, `dtype`
- Indexing, slicing, and accessing rows & columns
- Splitting data into features (`X`) and labels (`y`)
- Manual train-test split
- Handling missing values (`NaN`)
- Statistical operations (`mean`, `std`, `min`, `max`)
- Normalization and Standardization

### 2. `pandas_tutorial.ipynb` - Pandas for Data Analysis
- Reading CSV files (`pd.read_csv`)
- Data exploration: `head()`, `tail()`, `shape`, `info()`, `describe()`
- Column renaming
- Indexing with `iloc[]` and `loc[]`
- Filtering data with conditions
- Basic Exploratory Data Analysis (EDA)

### 3. `matplotlib_tutorial.ipynb` - Visualization with Matplotlib
- Creating histograms
- Visualizing feature distributions by class
- Customizing plots (titles, labels, legend, transparency)

### 4. `seaborn_tutorial.ipynb` - Statistical Visualization with Seaborn
- Creating scatter plots with hue (color by species)
- Setting plot styles
- Beautiful statistical visualizations

### 5. `Valentine_spending.ipynb`
- This analyzes how spending behavior varies based on different moods such as Happy, Excited, Sad, and Neutral.
- A boxplot visualization is used to show the distribution, median, and variability of spending across each mood category.
- The analysis helps identify patterns in emotional spending and provides insights into how mood influences financial decisions.

## 🛠 Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn

## 🚀 How to Run the Notebooks

### Option 1: Using Git

```bash
git clone https://github.com/mashraf02/data-science-practice.git
cd data-science-practice
