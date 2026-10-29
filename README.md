# 🏠 Smart Real_Estate Price Analysis

## 📌 About the Project

This project analyze housing data to understand why some properties are more expensive than others. It uses Python to clean the data, handle missing values, and create visualizations that make the information easier to understand.

## 🎯 Project Objectives

* Understand the housing dataset and its different features.
* Clean the data and handle missing values.
* Use graphs to study housing trends and price patterns.
* Find the main factors associated with house prices.
* Present useful insights for buyers and real-estate businesses.

## 🛠️ Tools and Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Data Cleaning and Preprocessing
* Exploratory Data Analysis (EDA)
* Data Visualization

## 📂 Dataset Details

**Dataset:** King County House Sales Dataset

The dataset contains information about houses, including their prices, sizes, locations, and construction details.

**Key Features:**

* **Property Size:** Living area and total lot size.
* **House Structure:** Bedrooms, bathrooms, and floors.
* **Property Quality:** House grade and condition.
* **Location:** Waterfront access, and view rating.
* **Construction Details:** Year built and renovation year.
* **Target Column:** `price`

## 🔍 Project Workflow

### 1. Understanding the Data

* Load the dataset using Pandas.
* Checked the number of rows and columns.
* Examined column names, data types, and statistical summaries.
* Identified missing values and unnecessary columns.
### 2. Data Cleaning

* Removed unnecessary columns where needed.
* Checked and corrected data types.
* Converted the date column into datetime format.
* Prepared the dataset for further analysis.

### 3. Missing Value Treatment

* Checked which columns contained missing values.
* Focused on missing values in the `bedrooms` and `bathrooms` columns.
* Used median imputation to fill missing values while reducing the influence of outliers.

### 4. Exploratory Data Analysis (EDA)

Used different graphs to explore the dataset and understand its main patterns:

* Histograms
* Scatter plots
* Box plots
* Correlation heatmaps

The analysis focused on:

* Distribution of house prices.
* Relationship between living area and price.
* Effect of bedrooms, bathrooms, and house grade.
* Impact of waterfront access and views.


### 5. Feature Analysis

Analyzed important property features to understand how they relate to house prices.

Additional features, such as house age, renovation status, and price per square foot, can also be used to make comparisons easier.

### 6. Data Visualization

Created charts using Matplotlib and Seaborn to present the findings clearly.

**Screenshots:**

<img width="400" height="250" alt="download" src="https://github.com/user-attachments/assets/ee8b7b48-7407-46a7-954a-3bc605879491" />

**Conclusion:**
Market mainly consists of affordable properties, with fewer luxury houses.

<img width="400" height="250" alt="download" src="https://github.com/user-attachments/assets/844c35e3-2537-4146-b469-0feb682cffc1" />

**Conclusion:**
Generally, houses with larger living areas have higher prices.

<img width="400" height="250" alt="download" src="https://github.com/user-attachments/assets/04e29767-67e0-4e7f-8f93-dc9bee400219" />

**Conclusion:**
Larger houses with better construction grades generally have higher prices

## 📊 Conclusion after DataVisualization

* Houses with larger living areas generally have higher prices.
* Construction grade is an important factor associated with property value.
* Bathrooms can provide useful information about house prices alongside other property features.
* Waterfront access, good views, and renovations can be associated with premium property prices.
* Lot size alone may not fully explain differences in house prices.

## 💡 What We Can Learn from This Project/Recommendations

* Buyers can compare properties using important features rather than price alone.
* Real-estate businesses can better understand the factors associated with property value.
* Property size and quality are useful when comparing similar houses.
* Data visualization makes it easier to identify trends and patterns in the housing market.

## ⚠️ Limitations

* The analysis does not consider inflation or changes in purchasing power.
* Location analysis is limited by the information available in the dataset.
* The project focuses on data analysis and visualization rather than building a house-price  prediction model.

## 🏁 Conclusion
* This project succesfully helped in cleaning and organizing real-estate data by handling missing values and improving data quality.
* This analysis showed key factors affecting house prices and provided useful insights to help buyers and real-estate businesses make better decisions.
