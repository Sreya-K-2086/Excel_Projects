### **Excel_Projects**


## **Project 1: Manufacturing Project - Bike Sales**

### **Overview**  
This project, titled **"Manufacturing Project - Bike Sales,"** demonstrates the creation of an interactive Excel dashboard tailored for analyzing customer demographics and purchasing behavior. It highlights the process of transforming raw data into actionable insights, with a focus on the manufacturing sector, specifically bicycle sales. The dashboard provides an interactive and user-friendly experience, enabling stakeholders to explore and analyze data dynamically.


### **Objectives**  
1. **Data Cleaning and Preparation:**  
   - Removed duplicates to ensure data integrity.  
   - Standardized column values (e.g., replacing abbreviations like "M" and "F" with "Male" and "Female" for clarity).  
   - Created new columns, such as **Age Categorized,** using logical formulas for better segmentation and visualization.  

2. **Data Analysis:**  
   - Conducted demographic analysis by attributes like marital status, gender, income, and commute distance.  
   - Explored relationships between income levels and purchasing decisions.  
   - Identified trends in customer behavior, such as age groups most likely to purchase bicycles.  

3. **Dashboard Creation:**  
   - Built an aesthetically appealing dashboard using chart types like bar graphs, line graphs, and clustered columns.  
   - Incorporated interactive filters (Slicers) to allow users to dynamically slice data by key demographics such as:  
      - **Marital Status**  
      - **Children**  
      - **Gender**  
      - **Region**

4. **Sheet Structure for Clarity and Accessibility:**  
   The workbook is organized into four structured sheets:  
   - **Sheet 1 (Raw Data):** Contains the unaltered raw data provided at the start.  
   - **Sheet 2 (Working Sheet):** Includes the cleaned and processed data, ensuring it is ready for analysis.  
   - **Sheet 3 (Pivot Tables):** Houses all the pivot tables used to create the dashboard's visualizations.  
   - **Sheet 4 (Dashboard):** The final dashboard where all visualizations are consolidated, offering an interactive and visually engaging user experience.


### **Key Features**
1. **Interactive Slicers for Enhanced Usability:**  
   Users can filter the dashboard by marital status, children, gender, and region to narrow down insights and answer specific business questions.

2. **Demographic-Based Visualizations:**  
   - **Average Income by Gender and Purchase Decision:**  
     A clustered column chart shows income distribution across genders and whether a bike was purchased, providing insights into target demographics.  
   - **Commute Distance Analysis:**  
     A bar chart highlights the commute distances of customers who purchased bikes, aiding in market segmentation.  
   - **Age Categorized Trends:**  
     A line graph showcases purchasing trends across age categories, revealing which segments are most engaged.

3. **Clean and Professional Layout:**  
   The dashboard is color-coordinated with a clean design to ensure usability and clarity. Visualizations are aligned, titled, and labeled for intuitive navigation.


### **Applications in Manufacturing**  
This project aids in understanding customer behavior to:  
- Identify target demographics for product marketing.  
- Tailor manufacturing and inventory strategies based on purchasing trends.  
- Enhance customer segmentation and engagement strategies.


### **Tools and Techniques**  
- **Tools Used:** Microsoft Excel  
- **Key Features Applied:** Pivot Tables, Conditional Formatting, Slicers, Logical Formulas, Data Validation  
- **Visualization Techniques:** Clustered Column Charts, Line Graphs, Bar Charts  


### **Dataset Link**  
[https://github.com/AlexTheAnalyst/Excel-Tutorial/blob/main/Excel%20Project%20Dataset.xlsx]





## **Project 2: World Bank Loan Portfolio Analysis**

### **Overview**  
This project, titled **"World Bank Loan Portfolio Analysis,"** provides an in-depth exploration of loan utilization, risk levels, and repayment patterns. The dashboard offers key insights into the allocation and utilization of funds across various financers and financial types, while also simulating loan repayment behaviors and projecting future values.


### **Objectives**  
1. **Data Cleaning and Preparation:**  
   - Removed duplicates and validated `Current Amount` and `Amount (USD)` columns for consistency.  
   - Added calculated fields for **Loan Utilization Ratio** and **Risk Level.**  
   - Standardized all currencies into USD for uniform analysis.  

2. **Data Analysis:**  
   - Examined total loans (allocated and utilized) across financial types.  
   - Analyzed loan utilization trends to identify high- and low-performing projects.  
   - Simulated future loan repayments using financial functions (PMT and FV).

3. **Dashboard Creation:**  
   - Developed interactive visualizations to provide stakeholders with actionable insights.  
   - Included slicers to dynamically filter data by key metrics like:
      - **Project Financial Type**  
      - **Risk Level**

4. **Sheet Structure for Clarity and Accessibility:**  
   - **Sheet 1 (Raw Data):** Contains the original data provided by the World Bank.  
   - **Sheet 2 (Working Sheet):** Includes cleaned and processed data with additional calculated fields.  
   - **Sheet 3 (Pivot Tables):** Aggregates data to support visualizations in the dashboard.  
   - **Sheet 4 (Dashboard):** Consolidates visualizations for a clean and interactive view.

### **Key Features**
1. **Interactive Slicers for Enhanced Usability:**  
   Users can filter the dashboard by financial type and risk level to explore specific insights.

2. **Key Metrics and Visualizations:**  
   - **Total Loans:**  
     A clustered bar chart comparing `Amount (USD)` and `Current Amount` for different financial types.  
   - **Loan Utilization Trends:**  
     A line chart showing how loan utilization changes over time.  
   - **Risk Level Distribution:**  
     A pie chart visualizing the proportion of loans categorized by risk levels.  
   - **Top Financers:**  
     A bar chart identifying the top financers by total contributions.  
   - **Future Value and Monthly Repayments:**  
     A pivot table and supporting visualizations summarizing average projected values and repayments.

3. **Clean and Professional Layout:**  
   The dashboard aligns visualizations neatly and uses consistent color schemes for readability.


### **Applications in Finance**  
This project helps financial analysts and stakeholders:  
- Monitor loan utilization and identify underperforming projects.  
- Forecast loan repayments and optimize financial planning.  
- Assess risk levels and improve funding allocation strategies.


### **Tools and Techniques**  
- **Tools Used:** Microsoft Excel  
- **Key Features Applied:** Pivot Tables, PMT, FV, Data Validation, Conditional Formatting, Slicers  
- **Visualization Techniques:** Pie Charts, Line Graphs, Clustered Bar Charts  


### **Dataset Link**  
[https://search.worldbank.org/api/v3/projects/all.xlsx]
