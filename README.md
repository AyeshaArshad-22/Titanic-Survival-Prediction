🚢 Titanic Survival Prediction
Project Overview
This project implements a comprehensive machine learning pipeline to predict passenger survival during the Titanic disaster. Using the classic titanic.csv dataset, the repository demonstrates advanced data preprocessing, exploratory data analysis (EDA), and classification modeling using Scikit-Learn (sklearn).

🚀 Key Features
Data Cleaning: Robust handling of missing values in Age, Cabin, and Embarked features.

Feature Engineering: Transformation of categorical variables and extraction of insights from passenger demographics.

Exploratory Data Analysis (EDA): In-depth visualizations using Seaborn and Matplotlib to identify survival correlations.

ML Pipeline: Implementation of multiple classification models including:

Logistic Regression

Decision Trees

Random Forest

Evaluation Metrics: Detailed analysis using Accuracy scores, Confusion Matrices, and ROC Curves.

📊 Dataset Description
The model uses the titanic.csv dataset, which includes the following key features:

Survived: (Target) 0 = No, 1 = Yes

Pclass: Ticket class (1, 2, or 3)

Sex: Passenger gender

Age: Age in years

SibSp / Parch: Number of siblings/spouses/parents/children aboard

Fare: Passenger fare

Embarked: Port of embarkation

How to Run
Clone the repo:

Bash
git clone https://github.com/YourUsername/Titanic-Survival-Prediction.git
Install requirements:

Bash
pip install -r requirements.txt
Open the Notebook:

Bash
jupyter notebook "TItanicClassificationAnd Modeling.ipynb"
Repository Structure
titanic.csv: The raw dataset.

TItanicClassificationAnd Modeling.ipynb: The main Python notebook with code and analysis.

requirements.txt: List of necessary Python libraries.

📈 Results
The project compares different models to find the most accurate predictor. Key findings include:

Gender was a significant predictor of survival (Female passengers had a much higher survival rate).

Class (Pclass 1) showed higher survival probability compared to lower classes.

Final model performance was validated using ROC-AUC curves to ensure reliability.

📂 Project Structure
Plaintext
├── titanic.csv                             # Raw Dataset
├── TItanicClassificationAnd Modeling.ipynb # Main Project Notebook
├── requirements.txt                        # Required Libraries
└── README.md                               # Project Documentation
📜 License
This project is open-source and available under the MIT License.
📜 License
This project is open-source and available under the MIT License.
