# 🏡 **Real Estate Market Analysis with Python** 📊

## **Overview**  
The real estate market is a dynamic and multifaceted industry, impacting professionals, investors, and policymakers. Understanding market conditions, customer behavior, and property characteristics is critical for making informed decisions.  

This project leverages **Python** to preprocess, analyze, and visualize real estate data, uncovering meaningful insights into property transactions and customer profiles for a leading real estate company. 🏢💼

---

## **Problem Statement** 🧐  
The client, a prominent real estate company, has collected extensive data on properties and their customers. The data is currently unprocessed, with missing values and inconsistencies, hindering meaningful analysis. The company seeks actionable insights to answer key questions, such as
- 👥 What age groups exhibit the highest buyer potential?  
- 🏠 Which property types perform best in terms of sales and satisfaction?  
- 🌍 How does deal satisfaction vary by region?  

To address these challenges, the data needs to be cleaned, merged, and analyzed to generate insights and visualizations for strategic decision-making.

---

## **Project Objectives** 🎯  
The primary objectives of this project are
1. **Data Preprocessing**  
   - 🧹 Handle missing values and inconsistencies.  
   - 🔄 Transform and standardize column data types.  
   - 🤝 Merge datasets to create a unified dataset for analysis.  

2. **Descriptive Statistics**  
   - 📊 Understand numerical and categorical data distributions.  
   - 🏠 Summarize property sales, satisfaction levels, and customer profiles.  

3. **Data Analysis**  
   - 🏢 Examine property sales by building type, country, and state.  
   - 👤 Explore customer demographics and behavior patterns.  
   - 💰 Investigate relationships between variables like age and property price.  

4. **Data Visualization**  
   - 📈 Create meaningful visualizations for insights such as:  
     - 🔥 Deal satisfaction by country and state.  
     - 📅 Monthly sales trends.  
     - 🏙️ Yearly sales per building type.

---

## **Technology Stack** 💻  
This project is built using the following tools and libraries:  
- **Python 3.12.4**- For data preprocessing, analysis, and visualization.  
- **Jupyter Notebook**: For an interactive coding environment.  

### **Python Libraries**
- **pandas** 📊- For data manipulation and cleaning.  
- **NumPy** 🔢- For numerical operations.  
- **Matplotlib** 🎨- For static visualizations.  
- **Seaborn** 🌸- For statistical data visualizations.  
- **Plotly** 📉- For interactive visualizations.  
- **datetime** ⏳- For date transformations and operations.

---

## **Case Description** 📋  

### **Background**  
This project revolves around two datasets  
1. **Properties Dataset** 🏘️- Contains details about properties, including property ID, building type, sale date, area, and price.  
2. **Customers Dataset** 👥- Includes customer ID, name, surname, date of birth, and other demographic information.  

The objective is to combine and preprocess these datasets to analyze customer behavior and property transactions.

---

## **Project Workflow** 🔄  

### **1. Data Preprocessing** 🧹  
- **Handle Missing Values** 🚫- Identify and appropriately manage missing entries across columns.  
- **Standardize Column Names** ✏️- Ensure consistency in column naming conventions (e.g., lowercase and underscore-separated).  
- **Transform Data Types** 🔄- Convert columns to appropriate data types (e.g., dates to datetime, categorical values to numerical).  
- **Remove Inconsistencies** 🧼- Address issues such as leading/trailing spaces in key columns (e.g., `customer_id`).  
- **Merge Datasets** 🔗- Combine properties and customers datasets on the `customer_id` column to form a unified dataset of 267 rows and 19 columns.

### **2. Descriptive Statistics** 📊  
- Analyze key variables using descriptive statistics to understand:  
  - 🏠 Sales performance by building type, country, and state.  
  - 👤 Customer age distribution and buyer behavior.  
  - 💵 Key numerical variable distributions, such as property price and area.

### **3. Data Analysis** 📈  
- 🧮 Examine age groups and their buying potential by categorizing ages into intervals.  
- 💰 Analyze property price distributions and create price bins for further insights.  
- 📉 Investigate relationships between customer demographics (e.g., age) and property-related metrics (e.g., price).

### **4. Data Visualization** 📅  
Create comprehensive visualizations to address key questions:  
- **Deal Satisfaction by Country** 🌍- Bar chart or heatmap.  
- **Monthly Revenue Trends** 📅- Time-series line chart.  
- **Apartments Sold by State** 🏠- Pareto chart with absolute and cumulative frequencies.  
- **Age Distribution** 🎂- Histogram with age intervals.  
- **Yearly Sales by Building Type** 🏢- Line graph or stacked bar chart.  

### **5. Insights and Recommendations** 💡  
Interpret the results to provide actionable insights for the client. For instance:  
- The age group **31-36** exhibits the highest buyer potential, indicating targeted marketing opportunities.  
- Certain building types outperform others in terms of revenue and deal satisfaction, guiding future investment decisions.

---

## **Setup Instructions** ⚙️  

### **Prerequisites** 🔧  
Ensure you have the following installed:  
- **Python 3.12.4** 🐍  
- **Jupyter Notebook** 📓  
