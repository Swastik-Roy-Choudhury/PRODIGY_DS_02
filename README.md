AUTHOR-SWASTIK ROY CHOUDHURY
TERMINAL
OUTPUT
--- Data Cleaning ---
Missing values:              Count
PassengerId      0
Survived         0
Pclass           0
Name             0
Sex              0
Age            177
SibSp            0
Parch            0
Ticket           0
Fare             0
Cabin          687
Embarked         2
Data types:
PassengerId      int64
Survived         int64
Pclass           int64
Name            object
Sex             object
Age            float64
SibSp            int64
Parch            int64
Ticket          object
Fare           float64
Cabin           object
Embarked        object
dtype: object
--- Exploratory Data Analysis ---
       PassengerId    Survived      Pclass        Name         Sex  ...       Parch      Ticket        Fare       Cabin    Embarked
count   891.000000  891.000000  891.000000  891.000000  891.000000  ...  891.000000  891.000000  891.000000  891.000000  891.000000       
mean    446.000000    0.383838    2.308642  445.000000    0.647587  ...    0.381594  338.528620   32.204208   16.629630    1.529742       
std     257.353842    0.486592    0.836071  257.353842    0.477990  ...    0.806057  200.850657   49.693429   38.140335    0.800254       
min       1.000000    0.000000    1.000000    0.000000    0.000000  ...    0.000000    0.000000    0.000000   -1.000000   -1.000000       
25%     223.500000    0.000000    2.000000  222.500000    0.000000  ...    0.000000  158.500000    7.910400   -1.000000    1.000000       
50%     446.000000    0.000000    3.000000  445.000000    1.000000  ...    0.000000  337.000000   14.454200   -1.000000    2.000000       
75%     668.500000    1.000000    3.000000  667.500000    1.000000  ...    0.000000  519.500000   31.000000   -1.000000    2.000000       
max     891.000000    1.000000    3.000000  890.000000    1.000000  ...    6.000000  680.000000  512.329200  146.000000    2.000000       

[8 rows x 12 columns]
