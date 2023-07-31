# Hector_G_Capstone
# Predicting MLB Player Salaries: A Batting Performance Analysis
## An In-Depth Exploratory Analysis of Factors Influencing Player Compensation

#### Author: Hector Guerrero
---

### Project Description
In this project, "Predicting MLB Player Salaries: A Batting Performance Analysis," we aim to build a model that accurately predicts Major League Baseball player salaries.

### Dataset
WAR Dataset (Baseball Reference): 121,375 rows, 48 columns. Covers all parts of player performance, including batting and pitching.
Batting Dataset (baseballdatabank - GitHub): 112,184 rows, 22 columns. Focuses on batting statistics for each season.
People Dataset (baseballdatabank - GitHub): 20,811 rows, 24 columns. Contains players' biographical details.
Salary Dataset (baseballdatabank - GitHub): 46,450 rows, 14 columns. Shows player salaries from 1985 to 2022, crucial for our analysis.
Teams Dataset (baseballdatabank - GitHub): 3,015 rows, 47 columns. Offers team-based statistics for each season.

Final Dataset for EDA and modeling: 22,010 Rows, 68 columns

### Files in the Repository
- Notebooks
  - I. Datasets Exploration and Merges
  - II. Data Preprocessing
  - III. EDA and Feature Selection
  - IV. Modeling
- Datasets
- Plots and Tableau
- Final Capstone Report (PDF)
- Hector_Guerrero_Capstone_Presentation (PDF)

### Tools and Libraries Used
- Jupyter Notebooks (Python)
    - Pandas
    - NumPy
    - Matplotlib
    - Seaborn
    - SciPy
    - scikit-learn

### Results and Findings
- Linear Regression (Baseline):
    - R² = 0.620.
    - RMSE = ±$3,222,420.69
- Decision Tree
    - R² = 0.785
    - RMSE = ±$2,422,400.47
- Random Forests
    - R² = 0.826
    - RMSE = ±$2,180,027.92
- __Gradient Boosting Regressor__
    - __R² = 0.841__
    - __RMSE = ±$2,080,887.37__

### Acknowledgments
- Datsets
    - https://github.com/chadwickbureau/baseballdatabank/tree/master
    - https://www.baseball-reference.com/data/

- Articles
    - https://www.baseballdatascience.com/category/machine-learning/
    - https://towardsdatascience.com/baseball-and-machine-learning-a-data-science-approach-to-2021-hitting-projections-4d6eeed01ede

### Contact Information
- Email: g.guerreroja@gmail.com
- GitHub: https://github.com/MemoGJ/
- LinkedIn: https://www.linkedin.com/in/hector-guillermo-guerrero-jauregui/


---




    
