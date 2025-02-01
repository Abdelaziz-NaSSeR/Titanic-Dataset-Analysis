# Titanic-Dataset-Analysis

I will analyze the Titanic passenger dataset to uncover patterns and
insights about survival factors during the Titanic disaster. You'll practice data cleaning, feature
engineering, and statistical analysis using pandas.

1. Data Cleaning
  a) Handle missing values:
    ● Fill missing ages using median age based on passenger class
    ● Handle missing values in 'Cabin' column
    ● Process missing values in 'Embarked' column
  b) Create new age categories:
    ● Child (0-15)
    ● Young Adult (16-30)
    ● Adult (31-45)
    ● Middle Aged (46-60)
    ● Senior (60+)

2. Feature Engineering
  Create the following new features:
  a) FamilySize:
    ● Combine 'SibSp' and 'Parch'
    ● Create a new column showing total family members
  b) Title from Name:
    ● Extract titles (Mr, Mrs, Miss, etc.) from passenger names
    ● Create a new column for titles
  c) Ticket Fare Analysis:
    ● Create fare ranges/bins
    ● Calculate fare per person for family groups
  d) Cabin Information:
    ● Extract deck information (first letter of cabin)
    ● Create a new column for deck

3. Basic Analysis
  Calculate and present:
  a) Survival rates by:
    ● Passenger class
    ● Gender
    ● Age category
    ● Deck
    ● Port of embarkation
  b) Family size impact:
    ● Analyze survival rates based on family size● Determine if traveling alone affected survival chances

4. Advanced Analysis
  Perform the following analyses:
  a) Create pivot tables showing:
    ● Survival rates by class and gender
    ● Survival rates by age group and class
    ● Survival rates by deck and class
  b) Statistical tests:
    ● Correlation between fare and survival
    ● Chi-square test for independence between categorical variables

5. Visualization
  Create at least three meaningful visualizations:
    ● Survival distribution by passenger class and gender
    ● Age distribution of survivors vs non-survivors
    ● Fare distribution analysis
    ● Family size impact on survival
