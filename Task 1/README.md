# AI & ML Internship - Task 1

## Data Cleaning & Preprocessing

### Objective

The objective of this task is to clean and prepare raw data for
Machine Learning.

### Dataset

The Titanic dataset was used for this task.

### Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

### Preprocessing Steps

1. Loaded and explored the Titanic dataset.
2. Checked for missing values.
3. Handled missing Age values using the median.
4. Handled missing Embarked values using the mode.
5. Removed the Cabin column because of its large number of missing values.
6. Removed unnecessary columns such as PassengerId, Name and Ticket.
7. Converted categorical variables using one-hot encoding.
8. Visualized numerical features using boxplots.
9. Detected and removed outliers using the IQR method.
10. Standardized numerical features using StandardScaler.
11. Saved the cleaned dataset as Titanic-Cleaned.csv.

### Files

- `titanic_preprocessing.ipynb` - Google Colab notebook containing the complete implementation.
- `Titanic-Dataset.csv` - Original dataset.
- `Titanic-Cleaned.csv` - Preprocessed dataset.
- `outliers_before.png` - Boxplot before outlier removal.
- `outliers_after.png` - Boxplot after outlier removal.
- `missing_values.png` - Missing-value visualization.

### Conclusion

The Titanic dataset was successfully cleaned and preprocessed.
Missing values were handled, categorical features were encoded,
outliers were removed using the IQR method, and numerical features
were standardized using StandardScaler.
