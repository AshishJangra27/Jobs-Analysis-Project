# **Jobs Analysis Project** 📊  

---

![Jobs Analysis Dashboard](https://raw.githubusercontent.com/AshishJangra27/Jobs-Analysis-Project/refs/heads/main/banner.png)

---

## **Overview**
This project delivers a comprehensive analysis of job market trends, focusing on:
- Demand for roles across various sectors.
- Key skill requirements and experience expectations.
- Salary benchmarks and compensation analysis.
- Identification of top hiring companies.  

The data is sourced from a GitHub repository and processed for actionable insights.  

---

## **Sample Data**
Below is a snapshot of the dataset structure with 5 random rows for better understanding:  

| job_id          | job_role                                     | company                                      | experience | salary                     | location                            | rating | reviews        | resposibilities                                                         |
|------------------|---------------------------------------------|---------------------------------------------|------------|----------------------------|-------------------------------------|--------|----------------|------------------------------------------------------------------------|
| 1.511226e+11    | Business Sales Manager - Banca | Life Insurance | Lavya Associates                            | 5-10 Yrs   | 6,00,000 - 8,00,000 PA.   | Jorhat                              | NaN    | NaN            | Life Insurance, BFSI, Bancassurance, team handling                      |
| 3.012220e+11    | HR Manager 1                                 | Emerald Paper Products                       | 2-7 Yrs    | 1,75,000 - 2,50,000 PA.   | Hybrid - Mohanlalganj               | NaN    | NaN            | Human Resource Management, hr, monitoring, Recruitment                 |
| 2.012350e+10    | Executive- DevOps Engineer                   | Rahi                                         | 3-8 Yrs    | Not disclosed             | Pune                                | NaN    | NaN            | Linux, Jenkins, web services, Gitlab, Puppet, DevOps                   |
| 5.012300e+10    | Operation Executive (Females Only)           | Eduworld Bangalore Educational Services      | 1-6 Yrs    | 1,25,000 - 2,50,000 PA.   | Trivandrum/Thiruvananthapuram       | NaN    | NaN            | Team Management, Team Handling, Team Leading, Brand Development        |
| 7.012350e+10    | Product Owner - Arcadis Gen                  | Arcadis Consulting India Pvt. Ltd            | 4-7 Yrs    | Not disclosed             | Noida, Mumbai                       | 4.2    | 145 Reviews    | Product management, Sales, SAP, Performance management                 |

---

## **Objectives**
- Map the distribution of job roles and industry demand.  
- Identify key skills and experience requirements.  
- Analyze salary patterns across regions and roles.  
- Highlight top hiring companies and their market impact.  

---

## **Data Processing**
- Handled **null values** and removed duplicates for data integrity.  
- Cleaned and standardized **salary** and **experience** fields.  
- Dropped irrelevant columns to streamline the analysis.  

---

## **Key Insights**
- **Market Landscape:** 72,967 job postings across 15,310 companies.  
- **Top Employers:** Identified market leaders based on review metrics.  
- **Role Analysis:** Data Analyst roles are in consistent demand.  
- **Skill Mapping:** Isolated core responsibilities across top roles.  
- **HDFC Bank:** Analyzed specific skill expectations.  

---

## **Visualizations**
- **Pie Charts:** Company-wise market share visualization.  
- **Bar Charts:** Top skills and responsibilities breakdown.  

---

## **Technologies Used**
- **Python:** Data manipulation and processing.  
- **Pandas:** Efficient data handling.  
- **Matplotlib & Seaborn:** Clear, insightful visualizations.  

---

## **Data Cleaning Summary**  
- **Removed Rows:**  
  - Entries with missing values in `job_id`, `resposibilities`, and `company`.  
- **Imputed Values:**  
  - **Experience:** ➡️ `5-10 Yrs`  
  - **Location:** ➡️ `Bangalore/Bengaluru`  
  - **Rating:** ➡️ `0.0`  
  - **Reviews:** ➡️ `0 Reviews`  

---

## **Duplicate Removal Summary**  
- All duplicate entries based on `job_id` were successfully removed, ensuring **data integrity** and **uniqueness**.  

---

## **Top 10 Companies by Minimum Reviews Analysis**  
- **Tata Consultancy Services (TCS)**, **Reliance Industries (RIL)**, and **HDFC Bank** lead the market with the highest review counts.  
- These companies dominate the market in terms of visibility and employee engagement.  

---

## **Top 10 Responsibilities by Frequency**  
- The most common responsibilities include **Sales**, **Communication**, and **Customer Service**.  
- Technical roles demand expertise in **JavaScript** and **Java**, reflecting high industry needs.  

---

## **Top 10 Responsibilities at HDFC Bank**  
- **Portfolio Management**, **Cross Selling**, and **Sales** are top responsibilities.  
- Reflects HDFC's focus on **customer relationship management** and **financial services**.  

---

## **Top 10 Responsibilities for Data Analysts**  
- Key skills include **Data Analysis**, **SQL**, and **Excel**.  
- Emerging technologies like **Power BI** and **Tableau** are also highly valued for data visualization.  

---

## **Future Enhancements**
- **Predictive Modeling:** For salary estimations and trend predictions.  
- **Regional Analysis:** Mapping hiring trends across cities for deeper insights.  
- **Skill Gap Analysis:** Identifying skill shortages to guide upskilling.  

---

## **Author**
- **Ashish Jangra** - [GitHub Profile](https://github.com/AshishJangra27)
- **Colab Link** - [Colab]([https://github.com/AshishJangra27](https://colab.research.google.com/drive/1E1CPo_6YyH6VfsMdEkSQ3eCXIgs5yJMM?usp=sharing))

---

## **License**
This project is licensed under the **CC License**.  
