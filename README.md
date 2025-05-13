#Capstone Data Analaytics Project

# GCP Data Analytics Pipeline for FinTech Treasury Operations

### Dashboard: ![GCDA Capstone Dashboard](https://github.com/user-attachments/assets/7204d1d8-d92a-4fd8-9c7b-6733a89c3b8c)



## Introduction

TheLook Fintech is a pioneering financial technology company that empowers independent online store owners by providing inventory loans. As a cloud data analyst, this project was focused on enhancing data-driven decision-making within the Treasury department, enabling the company to effectively track performance and facilitate growth. Utilizing Google BigQuery, the project aimed to collect, process, and store key financial data, addressing crucial business questions. A self-service dashboard was developed to visualize loan health data, allowing proactive management of the loan portfolio and fostering timely decision-making based on up-to-date insights.
##Tools/Tech 
* BigQuery
* SQL
* Looker Enterprise / Looker
* Google Sheets
* Excel

## Steps followed 

1. Data Preparation and Storage - 
* Created a BigQuery project and established necessary permissions
* Imported raw loan data into BigQuery standard tables
* Set up data structures to optimize query performance
* Established data security and access protocols

2. Data Cleaning and Processing - 
* Developed SQL queries to identify and filter duplicate records
* Implemented data deduplication process specifically for purpose data
* Validated data integrity through quality checks
* Established automated data refresh processes

3. SQL Query Development
   ![State Region Table Import GCDA Capstone Project](https://github.com/user-attachments/assets/c5314f7e-acff-4bf7-a8b7-e072eb08ac3f)

* Designed SQL queries to aggregate loan issuance data by day and year
* Created queries to analyze loan distribution patterns
* Developed parameterized queries for flexible reporting options
* Optimized query performance for large datasets

4. Report Generation
   ![Google Sheet of Customer data GCDA Capstone Project](https://github.com/user-attachments/assets/7c13cd77-6b39-4c9e-bd64-7a9c9dbe2f71)

* Generated comprehensive reports showing total loans issued by day
* Created annual loan issuance summary reports
* Implemented trending analysis for loan volumes
* Developed filtering mechanisms for detailed data exploration

5. Looker Enterprise Integration
   ![LS Studio Loan_with_region visualization Capstone Project](https://github.com/user-attachments/assets/db4c60d9-e7dd-4cdf-9007-36b8c97c7c13)

* Connected Looker Enterprise to BigQuery data source
* Created LookML models to define relationships between data elements
* Established measures and dimensions for analysis
* Set up appropriate access controls for dashboard users

6. Dashboard Development with Looker
   ![Screenshot 2025-05-12 171511](https://github.com/user-attachments/assets/e5042f25-5ec5-4fe4-80cc-2ecf418238bc)

* Utilized Looker's visualization tools to create interactive dashboards
* Implemented tile-based layout for organized presentation of loan health metrics
* Created custom visualizations including time-series charts, heat maps, and KPI indicators
* Built conditional formatting to highlight critical loan performance thresholds
* Incorporated Looker's filtering and parameter capabilities for user-driven analysis
* Designed dashboard for both desktop and mobile viewing experiences
* Implemented scheduled delivery of dashboard insights to stakeholders

7. Documentation and Knowledge Transfer
* Documented SQL queries and data transformations
* Created user guides for Looker dashboard navigation
* Recorded technical specifications for future maintenance
* Prepared executive summary of findings and methodologies

 

# Insights


##Growth Trends
* Observed substantial year-over-year growth in loan issuance, increasing from 2,594 loans in 2012 to 51,737 loans in 2019, representing a 1,895% increase over a 7-year period
* Identified a critical inflection point between 2014 (23,453 loans) and 2015 (41,919 loans), showing a 78.7% single-year growth spike that corresponds with the company's strategic expansion
* Noted more moderate but steady growth averaging 7.3% annually between 2015-2019, indicating market stabilization and sustained demand

##Business Maturity Indicators
* The substantial increase from 2014 to 2015 coincides with TheLook Fintech's transition from early-stage to growth-stage operations
* Growth pattern from 2017-2019 shows signs of market maturation with incremental increases rather than exponential growth
* Volume in recent years indicates successful market penetration and brand establishment

##Customer Profile Analysis
* Combined with customer data, loan volume growth correlates with expansion into new geographic markets, particularly in TX, OH, PA, NY, and FL
* Customer income data reveals that the 30,000−30,000−60,000 income bracket represents the largest segment of the loan portfolio

#Strategic Implications
###Portfolio Diversification
* The increasing loan volume necessitates enhanced risk management strategies to maintain portfolio health
* Geographic distribution analysis reveals opportunities to balance the portfolio across additional states with similar e-commerce potential
* Income and balance data suggest potential for new loan products targeting specific customer segments with demonstrated repayment capacity
#Operational Considerations
* The rapid scaling of loan issuance (particularly from 2014-2015) highlights the need for robust operational infrastructure to maintain service quality
* Data quality improvements, particularly around verification processes, should be prioritized to support the growing loan portfolio
* Historical growth patterns can inform more accurate forecasting for resource allocation and capital requirements

#Recommendations
##Short-term Actions
* Implement enhanced data validation procedures to address the high percentage of unverified customer information
* Develop targeted marketing strategies for consistent growth in 2020, building on the momentum from previous years
* Create segment-specific risk assessment models based on historical performance data from similar customer profiles

##Long-term Strategy
* Develop predictive analytics capabilities to forecast loan demand by geographic region and customer segment
* Establish proactive portfolio management protocols to maintain healthy loan performance as volume continues to increase
* Consider strategic expansion into complementary financial products that serve the existing customer base

### Creator
    Terrance Davis
    Email: tldavisj@syr.edu
    Linkedin: www.linkedin.com/in/terranceldavis
