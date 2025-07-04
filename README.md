# 🚀 Data Cleaning and Preprocessing – Titanic Dataset

🔗 **Google Colab Link**: [Click here to view in Colab](https://colab.research.google.com/drive/183EL1eA4f3pQWH9mR4VR-cW9K4qr00dc?usp=sharing)

---

## ✅ Objective

To learn and apply essential data cleaning and preprocessing techniques on a real-world dataset using Python tools. The goal is to make the dataset clean, consistent, and ready for machine learning model training.

---

## 📊 Dataset Used

- **Name:** Titanic Dataset  
- **Source:** [Kaggle Titanic - Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic/data)  
- **Description:**  
  The dataset contains information about passengers aboard the Titanic, which sank in 1912. It includes features such as age, gender, ticket class, and survival status. It is widely used for machine learning practice.

---

## 🛠️ Tools Used

- **Python** – Programming language used for data analysis and preprocessing tasks  
- **Pandas** – To load, explore, manipulate, and clean tabular data  
- **NumPy** – For numerical operations and handling arrays/missing values  
- **Matplotlib** – To create visualizations like boxplots for outlier detection  
- **Seaborn** – For advanced and attractive data visualizations  
- **Scikit-learn** – To perform imputation, encoding, and standardization (preprocessing)  

---

## 🔄 Steps Performed in Data Cleaning & Preprocessing

1. **Importing Libraries**  
   - Loaded essential libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, and `sklearn`.

2. **Loading the Dataset**  
   - Loaded the Titanic dataset using either a local CSV file or Seaborn’s built-in dataset.

3. **Exploring the Data**  
   - Checked shape, column types, and missing values using `.info()` and `.isnull().sum()`.

4. **Handling Missing Values**  
   - Imputed missing numeric values using **median**.  
   - Imputed missing categorical values using **most frequent (mode)**.

5. **Encoding Categorical Variables**  
   - Applied **One-Hot Encoding** using `pd.get_dummies()` to convert non-numeric columns to numeric.

6. **Normalizing/Standardizing Numeric Features**  
   - Used **StandardScaler** to scale numeric features (zero mean, unit variance).

7. **Visualizing and Removing Outliers**  
   - Plotted **boxplots** to visually inspect outliers.  
   - Used **IQR (Interquartile Range)** method to detect and remove outliers from the dataset.

8. **Final Clean Dataset**  
   - Created a cleaned and preprocessed dataset (`df_clean`) that is ready for machine learning.

---

📌 *This project demonstrates how to turn messy raw data into structured, reliable input for ML models.*  
💬 Feel free to fork, star ⭐, or suggest improvements!
