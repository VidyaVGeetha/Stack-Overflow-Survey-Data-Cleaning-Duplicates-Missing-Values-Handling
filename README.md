# Stack Overflow Survey — Data Cleaning: Duplicates & Missing Values Handling

This project performs basic data cleaning on the Stack Overflow Developer
Survey dataset. The notebook identifies and removes duplicate rows, analyzes
missing values, imputes missing entries in the RemoteWork column using the
most frequent value (mode), and detects compensation-related columns for
future analysis.

## ✅ Tasks Performed

### 1️⃣ Load Dataset
- Loaded the dataset into a Pandas DataFrame

### 2️⃣ Understand Dataset Structure
- Checked the shape of the dataset (rows and columns)

### 3️⃣ Finding and Removing Duplicates
- Checked whether duplicate rows exist
- Counted the number of duplicate rows
- Displayed duplicate records
- Removed duplicate rows using `drop_duplicates()`
- Verified the updated dataset shape

### 4️⃣ Finding Missing Values
- Counted missing values for all columns
- Displayed only columns that contain missing values
- Calculated total missing values in the dataset
- Counted missing values in the `RemoteWork` column

### 5️⃣ Imputing Missing Values (RemoteWork Column)
- Identified the most frequent (majority) value in `RemoteWork`
- Replaced missing values in `RemoteWork` with the majority value

### 6️⃣ Identifying Compensation-Related Columns
- Searched for column names containing `Comp` or `Salary`
- Listed compensation-related fields for further analysis

## 🧰 Libraries Used
- Python
- Pandas

## ▶️ How to Run
1. Open the notebook in Jupyter / JupyterLab
2. Install dependencies if required:
3. Run the cells step-by-step

## 🎯 Project Focus
This project is limited to:
- duplicate detection and removal
- missing-value analysis
- RemoteWork column imputation
- identifying compensation-related columns
