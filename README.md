- **Handling Missing Values**
  - Checked missing values per column
  - Dropped unnecessary columns
  - Filled missing values with mean or mode

- **Some Basic Analysis**
  - Counted unique value frequencies
  - Displayed sample rows for dataset overview

- **Feature Engineering**
  - Created FamilySize from SibSp + Parch
  - Created Cfamily categorizing family size
  - Binned Fare into ranges using pd.qcut
  - Extracted passenger Title from Name
  - Converted Title to categorical
  
  - **Univariate Analysis**
  - Explored min/max values for Age and Fare
  - Visualized distributions of Age, Fare, FamilySize, and categorical features
  - Analyzed survival by Pclass, gender, and family size

- **Numerical Analysis**
  - Created dummy variables for categorical features
  - Checked dataset shape before and after encoding
  - Visualized numeric feature relationships

- **Bivariate Analysis**
  - Compared survivors vs. non-survivors by Pclass, Embarked, and Age groups
  - Grouped and counted survival by Title, Pclass, and Embarked
  - Visualized relationships between features and survival