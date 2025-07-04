Data Cleaning  and Preprocessing – Titanic Dataset
Link of google colab:https://colab.research.google.com/drive/183EL1eA4f3pQWH9mR4VR-cW9K4qr00dc?usp=sharing

✅ Objective
To learn and apply essential data cleaning and preprocessing techniques on a real-world dataset using Python tools. 
This includes:
Importing and exploring raw data
Handling missing values through imputation
Encoding categorical variables into numerical form
Normalizing or standardizing numerical features
Detecting and removing outliers using boxplots
The final goal is to prepare a clean, structured, and machine learning-ready dataset.

📊 Dataset Used
Name: Titanic Dataset
Source: Kaggle Titanic - Machine Learning from Disaster
Description:
This dataset contains passenger information from the Titanic ship, which sank in 1912. It is widely used for machine learning and data analysis practice.

🧾 Key Features in the Dataset:
Column	Description
PassengerId	-Unique ID for each passenger
Survived	  -Target variable (0 = No, 1 = Yes)
Pclass	    -Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
Name	      -Passenger's name
Sex	        -Gender
Age	        -Age in years
SibSp	      -No. of siblings/spouses aboard
Parch	      -No. of parents/children aboard
Ticket	    -Ticket number
Fare	      -Ticket fare
Cabin	      -Cabin number (many missing values)
Embarked	  -Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

🛠️ Tools Used
Tool / Library	
-Python	        Programming language used for data analysis and preprocessing tasks
-Pandas	        To load, explore, manipulate, and clean tabular data
-NumPy	          For numerical operations and handling arrays/missing values
-Matplotlib	    To create visualizations like boxplots for outlier detection
-Seaborn	        For advanced and attractive data visualizations
-Scikit-learn	  To perform imputation, encoding, and standardization (preprocessing)

🔄 Steps Performed in Data Cleaning & Preprocessing
1.Importing Libraries
      -Loaded essential libraries: pandas, numpy, matplotlib, seaborn, and sklearn.
2.Loading the Dataset
      -Loaded the Titanic dataset using either a local CSV file or Seaborn’s built-in dataset.
3.Exploring the Data
      -Checked shape, column types, and missing values using .info(), .isnull().sum().
4.Handling Missing Values
      -Imputed missing numeric values using median.
      -Imputed missing categorical values using most frequent (mode).
5.Encoding Categorical Variables
      -Applied One-Hot Encoding using pd.get_dummies() to convert non-numeric columns to numeric.
6.Normalizing/Standardizing Numeric Features
      -Used StandardScaler to scale numeric features (zero mean, unit variance).
7.Visualizing and Removing Outliers
      -Plotted boxplots to visually inspect outliers.
      -Used IQR (Interquartile Range) method to detect and remove outliers from the dataset.
8.Final Clean Dataset
      -Created a cleaned and preprocessed dataset (df_clean) that is ready for machine learning.





