# Task 1: Titanic Dataset Analysis – Data Cleaning and Preprocessing

## 1. Problem Statement

The objective of this task is to clean and preprocess the Titanic dataset to make it suitable for further data analysis. Raw datasets may contain missing values, duplicate records, inconsistent data types, and unnecessary columns that can affect the accuracy of analysis.

This project focuses on identifying and handling missing values, removing duplicate records, converting data types where necessary, and renaming columns to improve data readability and consistency.

## 2. Dataset Details

**Dataset Name:** Titanic Dataset  
**Source:** Kaggle – Titanic: Machine Learning from Disaster  
**Dataset Link:** https://www.kaggle.com/competitions/titanic/data

**File Used:** `train.csv`

The dataset contains passenger information from the Titanic, including passenger class, age, gender, ticket fare, and survival status.

### Important Columns

| Column Name | Description |
|---|---|
| PassengerId | Unique passenger identification number |
| Survived | Survival status (0 = No, 1 = Yes) |
| Pclass | Passenger class (1st, 2nd, or 3rd) |
| Name | Passenger's name |
| Sex | Passenger's gender |
| Age | Passenger's age |
| SibSp | Number of siblings or spouses aboard |
| Parch | Number of parents or children aboard |
| Ticket | Ticket number |
| Fare | Passenger's ticket fare |
| Cabin | Cabin number |
| Embarked | Port of embarkation |

**Dataset Size:** 891 rows and 12 columns in the original training dataset.

### Tools and Libraries Used

- Python
- Pandas
- Jupyter Notebook / Google Colab

## 3. Approach

The following steps were performed to clean and preprocess the dataset.

### Step 1: Load the Dataset

The Titanic dataset was imported using Pandas. The first few rows were displayed to understand the structure and contents of the data.

### Step 2: Inspect the Dataset

The dataset was examined using functions such as `head()`, `info()`, and `isnull().sum()` to identify column names, data types, and missing values.

### Step 3: Handle Missing Values

- Missing values in the `Age` column were replaced with the median age.
- Missing values in the `Embarked` column were replaced with the most frequent value.
- The `Cabin` column was removed because it contained a large number of missing values.

### Step 4: Remove Duplicate Records

Duplicate rows were identified and removed using Pandas to avoid repeated records in the cleaned dataset.

### Step 5: Convert Data Types

Data types were checked and converted where necessary to ensure that numerical columns, such as `Age`, `Fare`, and `Survived`, were represented appropriately.

### Step 6: Rename Columns

Selected column names were changed to make them clearer and easier to understand.

Examples:
- `PassengerId` → `Passenger_ID`
- `Pclass` → `Passenger_Class`
- `SibSp` → `Siblings_Spouses`
- `Parch` → `Parents_Children`

### Step 7: Export the Cleaned Dataset

The cleaned dataset was saved as `Titanic_Cleaned.csv` for future analysis.

## 4. Results

After completing the data cleaning and preprocessing steps, the following outcomes were achieved:

- Inspected the dataset and identified missing values.
- Handled missing values in selected columns.
- Removed the `Cabin` column due to extensive missing data.
- Checked for and removed duplicate records.
- Verified and converted data types where necessary.
- Renamed selected columns for better readability.
- Exported the cleaned dataset as `Titanic_Cleaned.csv`.

### Output File

`Titanic_Cleaned.csv`

The output dataset is better organized and prepared for further data analysis and visualization.

## 5. Conclusion

This task demonstrates the importance of data cleaning and preprocessing in data analysis. By handling missing values, removing duplicate records, verifying data types, and renaming columns, the Titanic dataset was prepared for further analysis.

The project provided practical experience with Python and Pandas and demonstrated how raw data can be transformed into a cleaner, more consistent dataset.

## 6. Project Structure

```text
Task-1-Titanic-Data-Cleaning/
│
├── train.csv
├── Titanic_Cleaned.csv
├── Titanic_Data_Cleaning.ipynb
└── README.md
```

