# Titanic-Survival-Prediction
This is the original data from Titanic competition plus some changes that I applied to it to be better suited for binary logistic regression:

Merged the train and test data.

Removed the 'ticket' and 'cabin' attributes.

Moved the 'Survived' attribute to the last column.

Added extra zero columns for categorical inputs to be better suited for One-Hot-Encoding.

Substituted the values of 'Sex' and 'Embarked' attributes with binary and categorical values respectively.

Filled the missing values in 'Age' and 'Fare' attributes with the median of the data.
