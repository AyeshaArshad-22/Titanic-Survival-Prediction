🚢 Titanic Survival Prediction
Project Overview
This project implements a comprehensive machine learning pipeline to predict passenger survival during the Titanic disaster. Using the classic titanic.csv dataset, the repository demonstrates exploratory data analysis (EDA), robust data cleaning, and classification modeling to identify the key factors that influenced survival rates.

🚀 Key Features
Data Cleaning: Robust handling of missing values—specifically addressing the 177 missing Age values and 687 missing Cabin records.

Exploratory Data Analysis (EDA): In-depth visualizations using Seaborn to identify correlations between survival, gender, and ticket class.

ML Pipeline: Implementation of classification models, focusing on Logistic Regression and Random Forest.

Performance Evaluation: Detailed analysis using ROC Curves and Accuracy Scores to validate model reliability.

📊 Dataset Description
The model uses titanic.csv, featuring:

Survived: (Target) 0 = No, 1 = Yes.

Pclass: Ticket class (1st, 2nd, 3rd).

Sex & Age: Demographic information.

Fare: Price of the ticket.

Embarked: Port of embarkation (C, Q, S).

📈 Key Results
Gender Impact: Data confirms that female passengers had a significantly higher survival rate.

Socio-Economic Factor: Passengers in Pclass 1 had a higher probability of survival compared to other classes.

Model Validation: The final model was evaluated using RocCurveDisplay to ensure high predictive power.

🛠️ Installation & Setup
Clone the repo:

Bash
git clone https://github.com/AyeshaArshad-22/Titanic-Survival-Prediction.git
Install requirements:

Bash
pip install -r requirements.txt
Open the Notebook:

Bash
jupyter notebook "TItanicClassificationAnd Modeling.ipynb"
📂 Project Structure
Plaintext
├── titanic.csv                         # Raw Dataset
├── TItanicClassificationAnd Modeling.ipynb # Main Project Notebook
├── requirements.txt                    # Required Libraries
└── README.md                           # Project Documentation
📜 License
This project is open-source and available under the MIT License.
