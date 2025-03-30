# 📊 Data Analysis - Healthcare Access And Outcomes
The **Data Analysis - Healthcare Access And Outcomes** project focuses on data preparation and analysis using Python. The project involves processing a dataset related to **global health indicators**, including **obesity, tobacco use, and malaria prevalence by region**.
<br><br>

### ✨ Features
- **Dataset Filtering**: Extracts and processes relevant data from a dataset containing over 1,000 rows.
- **Data Cleaning**: Converts and standardizes numerical values for better analysis.
- **Exploratory Data Analysis**: Uses visualization and statistical techniques to understand trends in health indicators.
- **Machine Learning**: Implements clustering and regression models for predictive analysis.
<br>

### 🛠️ Technical Overview
- **Python**: Main programming language used for data analysis.
- **pandas & numpy**: Data manipulation and processing.
- **seaborn & matplotlib**: Data visualization libraries.
- **scikit-learn**: Used for clustering and regression analysis.
<br>

### 📁 File Structure
- **Project.ipynb**: Jupyter Notebook containing the full implementation of data analysis and visualization.
- **filtered_data_2022.csv**: Processed dataset used for analysis.
<br>

### 🚀 Getting Started
1. **Set Up Environment**: Ensure Python and Jupyter Notebook are installed.
2. **Install Dependencies**: Run the following command:
   ```sh
   pip install pandas numpy seaborn matplotlib scikit-learn
   ```
3. **Run the Notebook**: Open and execute `Project.ipynb` in Jupyter Notebook to analyze the dataset.
<br>

### 📊 Dataset Information
**Title:** Global Health Indicators Dataset 2022: Obesity, Tobacco Use, and Malaria Prevalence by Region  
**Source:** [Dataset file: web_download.xlsx](https://cdn.who.int/media/docs/default-source/gho-documents/world-health-statistic-reports/2024/web_download.xlsx?sfvrsn=4e7bbebd_1)
<br><br>

### 🔍 Data Processing Steps:
1. **Data Loading:**
   - Imported the dataset using `pandas`.
   - Extracted relevant data from the "data" sheet.
2. **Filtering:**
   - Selected data specifically from the year **2022**.
   - Ensured the dataset met the minimum requirement of **1,000 rows**.
3. **Data Cleaning:**
   - Adjusted numeric columns to a standardized decimal format.
   - Removed unnecessary characters and converted values to float.
4. **Exporting:**
   - Saved the cleaned dataset as `filtered_data_2022.csv`.
<br>
