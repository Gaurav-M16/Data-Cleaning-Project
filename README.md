# 📊 Exploratory Data Analysis (EDA) - Data Cleaning Project

## 📌 Project Overview

This project focuses on performing **Exploratory Data Analysis (EDA)** and **data cleaning** on a raw customer dataset using **Python** and **Pandas**.

The primary goal was to inspect the dataset, identify data quality issues, clean the data, and export a well-structured dataset for further analysis or machine learning tasks.

> **Note:** This dataset mainly contained textual information (names, phone numbers, emails, addresses, etc.), so the project focuses more on **data cleaning** than data visualization.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 📂 Project Structure

```
EDA-Exercise/
│
├── Dataset.csv              # Original dataset
├── Clean_Dataset.csv        # Cleaned dataset
├── EDA_Exercise.ipynb       # Jupyter Notebook
└── README.md
```

---

## 🔍 EDA Process

The following steps were performed during the analysis:

* Imported the required libraries
* Loaded the dataset
* Examined the first and last few rows
* Checked dataset dimensions
* Inspected column names and data types
* Generated descriptive statistics
* Identified missing values
* Checked for duplicate records
* Renamed columns for better readability
* Removed unnecessary columns
* Combined **First Name** and **Last Name** into a **Full Name** column
* Cleaned phone numbers by removing special characters (`-`, `.`, `+`, `x`, etc.)
* Converted phone numbers to integer format
* Exported the cleaned dataset as a new CSV file

---

## 🧹 Data Cleaning Performed

✔ Removed unwanted columns

✔ Renamed columns

✔ Combined first and last names into a single column

✔ Standardized phone numbers

✔ Converted appropriate columns to correct data types

✔ Exported a clean dataset

---

## 📈 Visualizations

This dataset did not contain meaningful numerical features suitable for visualization.

Since most columns were identifiers (names, phone numbers, emails, addresses, etc.), the focus of this project was **data cleaning and preprocessing** rather than graphical analysis.

---

## 📚 Skills Practiced

* Data Inspection
* Data Cleaning
* Data Transformation
* Feature Engineering
* Handling Missing Values
* Removing Duplicates
* Data Type Conversion
* String Manipulation
* Exporting Clean Data

---

## 🎯 Learning Outcome

Through this project, I learned how to:

* Explore an unfamiliar dataset
* Assess data quality
* Clean inconsistent data
* Perform common preprocessing tasks using Pandas
* Prepare datasets for future analysis and machine learning

---

## 🚀 Future Improvements

For future EDA projects, I plan to include:

* More advanced visualizations
* Correlation analysis
* Outlier detection
* Feature engineering
* Statistical analysis
* Interactive dashboards

---

## 👨‍💻 Author

**Gaurav Methe**

Aspiring Data Scientist | Python Developer | Machine Learning Enthusiast

---

⭐ If you found this project helpful, feel free to star the repository!
