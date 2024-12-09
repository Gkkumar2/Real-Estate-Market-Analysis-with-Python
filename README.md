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
## **Project Files** 📁  

- **realstate_data.csv** 🗂️- Cleaned dataset containing property and customer information.  
- **Realestate_Analysis.ipynb** 💻- Jupyter Notebook with all code and analysis https://github.com/Gkkumar2/Real-Estate-Market-Analysis-with-Python/blob/main/Realstate_Analysis.ipynb.  
- **README.md** 📑- Project documentation.

<div style="display: flex; justify-content: space-between;">
    <img src="https://github.com/Gkkumar2/Real-Estate-Market-Analysis-with-Python/blob/main/Screen_shots/Customer.jpg" alt="customer" style="width: 48%; height: 350px; object-fit: cover;">
    <img src="https://github.com/Gkkumar2/Real-Estate-Market-Analysis-with-Python/blob/main/Screen_shots/Screenshot%202024-12-08%20214139.png" alt="data types" style="width: 48%; height: 350px; object-fit: cover;">
</div>

- Both properties and customer datasets merged in to **Realstate** dataset using the customerid column
- Changed the column data to correct datatype 
  
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

Analyze key variables using descriptive statistics to understand:  
- 🏠 **Sales performance by building type, country, and state.**  
    
<div style="display: flex; justify-content: space-between;">
    <img src="https://github.com/Gkkumar2/Real-Estate-Market-Analysis-with-Python/blob/main/Screen_shots/Total%20revenue%20by%20type%20of%20the%20property.png" alt="type" style="width: 32%; height: 200px; object-fit: cover;">
    <img src="https://github.com/Gkkumar2/Real-Estate-Market-Analysis-with-Python/blob/main/Screen_shots/revenue%20by%20country.png" alt="country" style="width: 32%; height: 200px; object-fit: cover;">
    <img src="https://github.com/Gkkumar2/Real-Estate-Market-Analysis-with-Python/blob/main/Screen_shots/total%20revenue%20by%20state.png" alt="state" style="width: 32%; height: 200px; object-fit:cover;">
</div>

#### 💡 Insights  

- **Property Distribution**:  
  Apartments dominate the listings, accounting for **97%** of all properties, while offices represent only **3%**.  

- **Total Property Value**:  
  The combined value of listed properties is **$73M** for apartments and **$1.99M** for offices, including both sold and unsold properties.  

- **Average Prices**:  
  The average listing price for an apartment is **$284.2K**, whereas office properties are listed at an average of **$248.8K**.  

- **Revenue by Country**:  
  The **United States** generates the majority of the revenue, with **91%** of the listed properties located there.  

- **Top-Performing State**:  
  **California** leads in revenue generation, contributing over **$33M** to the total sales.  


- 👤 **Customer age distribution and buyer behavior.**
  
<div style="display: flex; justify-content: space-between;">
    <img src="https://github.com/Gkkumar2/Real-Estate-Market-Analysis-with-Python/blob/main/Screen_shots/age%20distribution.png" alt="age distribution" style="width: 32%; height: 200px; object-fit: cover;">
    <img src="https://github.com/Gkkumar2/Real-Estate-Market-Analysis-with-Python/blob/main/Screen_shots/revenue%20by%20age%20group.png" alt="Total revenue by age" style="width: 32%; height: 200px; object-fit: cover;">
    <img src="https://github.com/Gkkumar2/Real-Estate-Market-Analysis-with-Python/blob/main/Screen_shots/avg%20price%20age%20group.png" alt="avrage spent on the properties by age " style="width: 32%; height: 200px; object-fit: cover;">
  </div>

#### 💡 Insights  

- **Customer Age Distribution**:  
  The majority of customers fall within the **30-50 age range**, indicating a strong market presence in this demographic.  

- **Revenue by Age Group**:  
  - The **36-42 age group** generated the highest revenue, contributing **$10M**.  
  - The **31-36** and **42-48 age groups** each generated around **$6.5M** in revenue.  
  - The **71-76 age group** contributed the lowest revenue, with **$775K**.  

- **Spending Patterns by Age**:  
  Customers aged **19 to 48** tend to spend more on average when purchasing properties. In contrast, those aged **49 and older** exhibit lower average spending on property purchases.  

- **Property Purchases by Age Group**:  
  - The **36-42 age group** purchased the highest number of properties (**35**).  
  - Both the **31-36** and **42-48 age groups** followed closely, each purchasing **24 properties**.  


- 💵 **Key numerical variable distributions, such as property price and area.**  

<div style="display: flex; justify-content: space-between;">
    <img src="https://github.com/Gkkumar2/Real-Estate-Market-Analysis-with-Python/blob/main/Screen_shots/AVG%20price%20by%20property%20type.png" alt="age distribution" style="width: 32%; height: 200px; object-fit: cover;">
    <img src="https://github.com/Gkkumar2/Real-Estate-Market-Analysis-with-Python/blob/main/Screen_shots/avg%20area%20by%20property.png" alt="Total revenue by age" style="width: 32%; height: 200px; object-fit: cover;">
    <img src="https://github.com/Gkkumar2/Real-Estate-Market-Analysis-with-Python/blob/main/Screen_shots/avg%20price%20by%20mor%20and%20type.png" alt="avrage spent on the properties by age " style="width: 32%; height: 200px; object-fit: cover;">
  </div>

#### 💡 Insights  

- **Average Listing Prices**:  
  - Apartments are listed at an average price of **$284.2K**, while office properties average **$248.8K**.  

- **Average Property Area**:  
  - Apartments have an average area of **939 ft²**, and office properties average **835 ft²**.  

- **Impact of Mortgages on Pricing**:  
  - Properties with mortgages tend to have higher average prices compared to those without mortgages.  
  - Apartments:  
    - With mortgage: **$247.5K**  
    - Without mortgage: **$268K**  
  - Office Properties:  
    - With mortgage: **$268K**  
    - Without mortgage: **$233K**  

- **Correlation Between Area and Price**:  
  - There is a strong positive correlation (**0.95**) between **area** and **price**, indicating that as property area increases, its price also rises.  

<div style="display: flex; justify-content: space-between;">
  <img src="https://github.com/Gkkumar2/Real-Estate-Market-Analysis-with-Python/blob/main/Screen_shots/correlation.png" alt="Correlation Graph" style="width: 42%; height: 200px; object-fit: cover;">
</div>


---
### **3. Data Analysis** 📈  
- 🧮 Examine age groups and their buying potential by categorizing ages into intervals.  
- 💰 Analyze property price distributions and create price bins for further insights.  
- 📉 Investigate relationships between customer demographics (e.g., age) and property-related metrics (e.g., price).

### **4. Data Visualization** 📅  
---

Below are the key visualizations addressing critical questions. 

---

#### **1. Deal Satisfaction by Country and State 🌍**  

🌍 **Country Chart**  
--
<div style="display: flex; justify-content: space-between;">
    <img src="https://github.com/Gkkumar2/Real-Estate-Market-Analysis-with-Python/blob/main/Screen_shots/average%20deal%20satisfacrtion%20by%20country.png" alt="country" style="width: 48%; height: 250px; object-fit: cover;">
    <img src="https://github.com/Gkkumar2/Real-Estate-Market-Analysis-with-Python/blob/main/Screen_shots/satis-%20country-type.png" alt="country-type" style="width: 48%; height: 250px; object-fit: cover;">
  </div> 

#### 📝 **Insights**  

- **Customer Satisfaction by Country**:  
  - **Canada** and **Germany** have the **highest customer satisfaction scores** of **5 out of 5**, but this is likely due to the **small number of properties** listed in these countries.  
  - In contrast, the **USA** has an **average customer satisfaction score of 3.58**, reflecting a larger dataset.  

- **Customer Satisfaction by Property Type**:  
  - In the **USA**, apartments have an average satisfaction score of **3.57**, while office properties score slightly higher at **3.86**.  
  - **Canada** and **Germany** maintain **perfect satisfaction scores** across apartment listings.  

--

🗺️ **State Chart**  

<div style="display: flex; justify-content: space-between;">
    <img src="https://github.com/Gkkumar2/Real-Estate-Market-Analysis-with-Python/blob/main/Screen_shots/satis-state.png" alt="state" style="width: 48%; height: 250px; object-fit: cover;">
    <img src="https://github.com/Gkkumar2/Real-Estate-Market-Analysis-with-Python/blob/main/Screen_shots/satis-state-type.png" alt="state-type" style="width: 48%; height: 250px; object-fit: cover;">
  </div>  

#### 📝 **Insights:**  

- **Customer Satisfaction by State**:  
  - Customers who purchased properties in **Virginia** are the **most satisfied**, with an average rating of **4.5**.  
  - **California** follows with the **second-highest satisfaction score** of **3.75**.  
  - Satisfaction scores for other states range between **3** and **3.75**.  
  - Properties listed without a state mentioned (categorized as **Other Countries**) have an average satisfaction rating of **3.64**.  

- **Customer Satisfaction by Property Type**:  
  - For apartments, **Virginia** stands out with the **highest customer satisfaction score** of **4.5**.  
  - For office properties, **Nevada** leads with a **perfect satisfaction score of 5**.  


---

#### **2. Monthly Revenue Trends 📅**  

📈 **Revenue Chart**  

<div style="display: flex; justify-content: space-between;">
    <img src="https://github.com/Gkkumar2/Real-Estate-Market-Analysis-with-Python/blob/main/Screen_shots/monthely%20revenue%20per%20year.png" alt="revenue" style="width: 98%; height: 250px; object-fit: cover;">
 </div> 

#### 📝 **Insights:**  

- **Peak Performance**: November 2007 saw the **highest monthly revenue** at **$4.69M**, showcasing exceptional sales performance during that period.  
- **Lowest Revenue**: The **lowest monthly revenue** was observed in May 2005, totaling **$215k**, indicating a potential market slowdown or fewer transactions.  
- **Revenue Spikes**: Key **growth periods** were identified in **July 2005**, **September 2006**, **March 2007**, and **November 2007**, highlighting strategic sales or market demand surges.  
- **Revenue Decline**: A notable **drop in revenue** occurred between **March 2007** and **July 2007**, falling from **$3.5M** to **$1.5M**, signaling potential seasonality or market challenges.  
- **Stable Performance**: Years like **2004** and **2008** displayed **consistent revenue trends**, indicating periods of steady market activity.  

<div style="display: flex; justify-content: center;">
  <img src="https://github.com/Gkkumar2/Real-Estate-Market-Analysis-with-Python/blob/main/Screen_shots/monthly_revenue_trends.png" alt="Monthly Revenue Trends" style="width: 75%; height: auto; object-fit: contain;">
</div>
 

---

#### **3. Apartments Sold by State 🏠**  

🤝 **State Revenue Chart:** 

<div style="display: flex; justify-content: space-between;">
    <img src="https://github.com/Gkkumar2/Real-Estate-Market-Analysis-with-Python/blob/main/Screen_shots/number%20of%20properties%20sold%20by%20state.png" alt="state" style="width: 48%; height: 250px; object-fit: cover;">
    <img src="https://github.com/Gkkumar2/Real-Estate-Market-Analysis-with-Python/blob/main/Screen_shots/total%20revenue%20by%20state.png" alt="state-type" style="width: 48%; height: 250px; object-fit: cover;">
  </div>   

📝 **Insight:**  
_(Write your insights here)_  

---

#### **4. Age Distribution 🎂**  

👥 **Age Distribution Chart:**  
<div style="display: flex; justify-content: space-between;">
    <img src="https://github.com/Gkkumar2/Real-Estate-Market-Analysis-with-Python/blob/main/Screen_shots/age%20groups.png" alt="age groups" style="width: 48%; height: 250px; object-fit: cover;">
    <img src="https://github.com/Gkkumar2/Real-Estate-Market-Analysis-with-Python/blob/main/Screen_shots/revenue%20by%20age%20group.png" alt="revenue by age_group" style="width: 48%; height: 250px; object-fit: cover;">
  </div> 

📝 **Insight:**  
_(Write your insights here)_  

---

#### **5. Yearly Sales by Building Type 🏢**    

🗓️ **Sales Charts**  

<div style="display: flex; justify-content: space-between;">
    <img src="https://github.com/Gkkumar2/Real-Estate-Market-Analysis-with-Python/blob/main/Screen_shots/yearly%20sales%20by%20building.png" alt="sales by bulding" style="width: 48%; height: 250px; object-fit: cover;">
    <img src="https://github.com/Gkkumar2/Real-Estate-Market-Analysis-with-Python/blob/main/Screen_shots/yearly%20revenue%20by%20building.png" alt="revenue by building" style="width: 48%; height: 250px; object-fit: cover;">
  </div> 

📝 **Insight:**  
_(Write your insights here)_  

---
  

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
