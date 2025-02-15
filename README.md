# **TechnoEdge Sales Analysis Report**

## **Project Overview**
## **Effortless Email Data Appending: Automated Without Manual Intervention**
This project can be a fully automated sales analysis system in Power BI, designed to process monthly sales data received via email attachments. While the current implementation focuses on appending multiple files in a folder using Power Query, the concept can be extended to full automation.

In a fully automated setup, Power BI could connect directly to an organizational email inbox, extract sales data from attachments using Power Query Editor, and update the dashboard automatically—provided that email attachments maintain the same column name structure.

[VIEW FILE HERE](https://app.powerbi.com/view?r=eyJrIjoiZTdhZTJhN2UtOWQxNy00NjhlLWE4NDctYjAzNjM4M2FkMGQxIiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9)

### **Current Implementation: Appending Multiple Files in Power Query**
Appending Sales Data – Multiple files stored in a folder are appended using Power Query Editor, ensuring a seamless data refresh.

### **Future Automation Concept: Key Steps**

1. **Direct Email Integration** – Power BI connects to an **organizational email** to fetch attachments automatically.

GET DATA→EXCHANGE→MICROSOFT EXCHANGE ONLINE→ORGANIZATIONAL EMAIL ID(WITH ACCOUNT CREDENTIALS AND PERMISSIONS)
![EMAIL INTEGRATION](https://github.com/user-attachments/assets/af60a0c8-a306-4e5b-b35e-273141e19e50)

NAVIGATOR WINDOW→DISPLAY OPTIONS→ SELECT MAIL 

**2.Data Extraction & Transformation** –Once mail table contents are extracted ,To extract attachments from the attachment column- Use **Excel.Workbook(ColumnName)** to filter and extract relevant sales data while removing unnecessary columns.
![ATTACHMENTY COLUMN](https://github.com/user-attachments/assets/14ddc997-6ffa-49ec-9c1c-61a3f74644ad)


**3.Automated Data Loading & Visualization** – Extracted data is loaded into Power BI for real-time analysis.

![sales report1](https://github.com/user-attachments/assets/63e6f157-8d4a-43ce-b7ab-56658e48e8f4)

**4.Scheduled Refresh & Auto-Update** – Any **new sales email** received updates the dashboard upon dataset refresh in Power BI Service, provided the email files should follow same format with same column name and structure as loaded files to get append in power query.

### **Data Processing & Features Used:**

- **Folder Option in Get Data** – Here we Combine **48 monthly CSV files** into a single dataset for analysis. The files updated in the folder gets auto update manually to  get appended in power query.

![file folders](https://github.com/user-attachments/assets/c1ac4d7a-de46-4858-9b21-91ccffd24e72)

- **Power Query Transformations** – Cleans, structures, and prepares data for reporting.
- **Scheduled Refresh** – Ensures the dashboard remains updated without manual effort.
SALES REPORT2 IMAGE(attached in files section) IS THE REPORT AUTO-UPDATED WITH SALES DATA OF YEAR 2022.

## **Key Business Questions Addressed**

- What are the **total sales, profit, quantity, and discounts**?
- How do sales vary across **Segments, Categories, and Sub-Categories**?
- What are the **yearly and quarterly sales trends**?
- Which **state and region** contribute the most to revenue?

## **Insights & Findings**

### **A. Overall Sales Performance**

- **Total Sales:** **1.79M**
- **Total Profit:** **232.89K**
- **Total Quantity Sold:** **30K**
- **Total Discount Offered:** **1.23K**
- **Number of Orders:** **7,901**

### **B. Sales Distribution by Customer Segment**

- **Consumer Segment** contributes the highest sales (**49.38%**).
- **Corporate Segment** follows with **31.8%**, while **Home Office** accounts for **18.89%**.

### **C. Sub-Category Analysis**

- **Leading Sub-Category:** chairs **(249K in sales)**
- **Other High-Selling Sub-Categories:** phones, Storage, and Tables.

### **D. Sales Trends Over Time**

- **2021 - Q4** recorded the highest sales.
- Sales have grown steadily from **2019 to 2021**, with significant increases in the **East and West regions**.

### **E. Regional & State Performance**

- **Top Region:** **West (31.78%)**, followed by **East (30.54%)**.
- **Best Performing State:** **California** leads in sales

## **Conclusion**

This **end-to-end automation idea eliminates manual intervention**, ensuring seamless updates and **real-time insights** . By leveraging **automated email integration, Power Query transformations, and scheduled refresh**, the company can make **data-driven decisions effortlessly**.
