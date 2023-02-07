# Boston-Housing-Price-Prediction

In this project our goal is to predict the boston housing price according to given attribute by applying linear regression which is supervised machine learning algorithm. we use linear regression because we have to predict continuos value.

This boston housing dataset consist following attribute :

### Attribute Information (in order):

        - CRIM     per capita crime rate by town
        
        - ZN       proportion of residential land zoned for lots over 25,000 sq.ft.
        
        - INDUS    proportion of non-retail business acres per town
        
        - CHAS     Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
        
        - NOX      nitric oxides concentration (parts per 10 million)
        
        - RM       average number of rooms per dwelling
        
        - AGE      proportion of owner-occupied units built prior to 1940
        
        - DIS      weighted distances to five Boston employment centres
        
        - RAD      index of accessibility to radial highways
        
        - TAX      full-value property-tax rate per $10,000
        
        - PTRATIO  pupil-teacher ratio by town
        
        - B        1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
        
        - LSTAT    % lower status of the population
        
        - MEDV     Median value of owner-occupied homes in $1000's
        
#### Correlation & feature selection finding :

#### From above we can say that column "RM" is highly correlated with "MEDV" which is greater than 0.5 is 0.7
#### so we can say here "RM" is dependant variable and "MEDV" is independant variable.
#### "MEDV" is our target column.
#### target column is always a dependant variable.
#### Dependant variable = "MEDV" (Targer variable)
#### Independant variable = "RM" (Feature variable)
