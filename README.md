# Internship_task1
The sinking of the Titanic in 1912 was a tragic event, and this project aimed to understand the factors that influenced survival outcomes. Using passenger data such as age, gender, and socio-economic class, I developed a model to predict who was more likely to survive.

# Objective
The main objective of this project is to build a predictive model that can determine the types of people who were more likely to survive the Titanic disaster. The dataset used for this project contains information about passengers, including their age, gender, socio-economic class, and survival status.

# Dependencies
Python 3.x Jupyter Notebook (for running the project notebook)

# Dataset
The project uses two CSV files: train.csv and test.csv, which contain the training and test data, respectively. The dataset includes the following columns: PassengerId: Unique identifier for each passenger Survived: Target variable (0 = did not survive, 1 = survived) Pclass: Socio-economic class of the passenger (1 = Upper, 2 = Middle, 3 = Lower) Name: Passenger's name Sex: Passenger's gender Age: Passenger's age SibSp: Number of siblings/spouses aboard Parch: Number of parents/children aboard Ticket: Ticket number Fare: Fare paid by the passenger Cabin: Cabin number Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

# Data Preprocessing
In the data preprocessing phase, the following steps were performed:

Handling missing values: Missing values in the Age and Fare columns were imputed using the median value. Encoding categorical variables: The Sex column was label-encoded to convert it from categorical to numerical. Feature scaling: The Age and Fare columns were scaled using standardization.

# Model Training
For this project, we used the XGBoost algorithm to train the predictive model. XGBoost is known for its ability to handle complex relationships and missing data, making it suitable for this task.

# Evaluation
The model was evaluated using accuracy as the evaluation metric. After training the model on the training data, it achieved an accuracy score of [mention the accuracy score].


# Results
The analysis revealed interesting insights into the factors influencing survival on the Titanic. The correlation matrix highlighted the relationships between different features and the target variable.

# Contact
Feel free to contact me if you have any questions or feedback regarding this project. You can reach me at mohitkatare7620@gmail.com
