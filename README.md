Titanic Survival Prediction

This project predicts whether a Titanic passenger survived based on features like age, gender, ticket class, fare, and cabin. It uses the Titanic dataset from Kaggle, showcasing fundamental machine learning concepts.

Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Data Description](#data-description)
- [Modeling Techniques](#modeling-techniques)
- [Results](#results)
- [License](#license)

 Installation
```bash
pip install -r requirements.txt
```

## Usage
Run the main script to train the model and make predictions:
```bash
python titanic_survival_prediction.py
```

## Data Description
The dataset includes:
- `PassengerId`: Unique ID for each passenger
- `Survived`: Survival (0 = No, 1 = Yes)
- `Pclass`: Ticket class (1, 2, 3)
- `Name`: Passenger name
- `Sex`: Gender
- `Age`: Age
- `SibSp`: Number of siblings/spouses aboard
- `Parch`: Number of parents/children aboard
- `Ticket`: Ticket number
- `Fare`: Fare paid
- `Cabin`: Cabin number
- `Embarked`: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## Modeling Techniques
- Data preprocessing and cleaning
- Exploratory data analysis
- Logistic Regression and Random Forest classification

## Results
The model achieved an accuracy of XX% on the test dataset. Visualizations are included to showcase feature importance and model performance.

## License
This project is licensed under the MIT License.

