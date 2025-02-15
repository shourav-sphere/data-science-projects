# Titanic Dataset Analysis Project

This project performs a fundamental data science analysis on the Titanic dataset to explore patterns and trends related to passenger survival.

## Project Overview
The Titanic disaster is one of the most infamous shipwrecks in history. Using data analysis techniques, this project investigates factors that influenced survival outcomes.

## Dataset
The dataset used for this project is the Titanic dataset from Kaggle, which includes the following key features:
- **PassengerId**: Unique ID for each passenger
- **Survived**: Target variable (0 = No, 1 = Yes)
- **Pclass**: Passenger class (1 = 1st, 2 = 2nd, 3 = 3rd)
- **Name**: Name of the passenger
- **Sex**: Gender
- **Age**: Age
- **SibSp**: Number of siblings/spouses aboard
- **Parch**: Number of parents/children aboard
- **Ticket**: Ticket number
- **Fare**: Passenger fare
- **Cabin**: Cabin number
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## Project Structure
- **Data Preprocessing**: Handling missing values, encoding categorical variables, and feature scaling.
- **Exploratory Data Analysis (EDA)**: Visualizing data distributions, correlations, and survival patterns.
- **Statistical Insights**: Analyzing relationships between variables and survival outcomes.

## Tools & Libraries
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook

## Instructions to Run the Project
1. Clone the repository:
    ```bash
    git clone https://github.com/shourav-sphere/data-science-projects.git
    ```
2. Navigate to the project directory:
    ```bash
    cd titanic-survival-analysis
    ```
3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Open the notebook:
    ```bash
    jupyter notebook titanic-survival-analysis.ipynb
    ```

## Results
The analysis reveals that survival rates were significantly influenced by factors such as passenger class, gender, and age. Key insights include higher survival rates for women and first-class passengers.

## Contributing
Contributions are welcome! Please submit a pull request for any improvements or bug fixes.

## License
This project is licensed under the MIT License.

## Acknowledgments
- Titanic dataset provided by [Kaggle]
- Python community for providing amazing tools and resources.
