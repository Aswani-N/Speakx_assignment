# Speakx_assignment
REPORT ON THE DATASET

*This report present an analysis of the dataset which we have.The dataset is loaded and examined using python's pandas library.

1)LOADING THE DATASET
          
       * Imports necessary libraries numpy and pandas.
       *Specifies the file path to the dataset.
       *Uses pd.read_csv to load the dataset into a DataFrame.
       *Displays the first few rows of the dataset to verify successful loading.
   

2)FINDING THE MISSING VALUES

      *Checking the Shape of the Dataset (df.shape)
      *Detecting Missing Values(df.isnull())
      *Summarizing Missing Values by Column(df.isnull().sum())
      *Total Count of Missing Values in the Dataset(df.isnull().sum().sum())

   Using  these codes we get zero so its clearly saying that this dataset doesnot have missing values.

3)ENCODE CATEGORICAL VARIABLES
  
    *Label encoding assigns a unique numerical value to each category in a categorical variable.
    *This method is suitable for ordinal categorical data, where there is an inherent order among the categories.
    *Categorical columns such as partner,dependents,phoneservice,multiplelines...... we encode these columns using label encoder

4) Exploratory Data Analysis

   *Exploratory Data Analysis (EDA) is a crucial initial step in data analysis, aimed at understanding the characteristics of the dataset.
   *first describe the dataset.
   *find the head and tail of the dataset.
   *information  of the dataset.
   * using corr() function we find the correlation of the dataset.
   *use Data Visualisation
   *we draw heat map and boxplot.

 Here our target is churn and others are inputs.






     

    
