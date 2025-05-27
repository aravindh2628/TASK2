Titanic Dataset EDA

This project performs an Exploratory Data Analysis (EDA) on the Titanic dataset using Python libraries including Pandas, Seaborn, Matplotlib, and Plotly. The goal is to visualize data distributions, correlations, and patterns based on passenger features like age, class, fare, and survival.
📁 Dataset

The Titanic dataset is loaded directly using seaborn’s built-in load_dataset('titanic') function. It includes fields like:

Passenger class, sex, age

Fare paid

Survival status

Embarked port

📊 Analysis Performed

Display of the first few rows and summary statistics

Detection of missing values

Boxplots for numeric features

Correlation heatmap

Pairplots for numerical columns

Average fare by passenger class

Interactive scatter plot (Fare vs Age by Sex)

📦 Libraries Used

pandas

seaborn

matplotlib

plotly

▶️ How to Run

1.Clone the repo or download the notebook.

2.Make sure you have the required libraries installed:

bash
pip install pandas seaborn matplotlib plotly

3.Run the notebook using Jupyter:

bash
jupyter notebook Untitled1.ipynb

📌 Output

The notebook will generate visualizations including:

Correlation matrix

Boxplots

Pairplots

Interactive scatter plot using Plotly

