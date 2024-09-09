# DataAnalyst-AWS-Preeti
# Project 1 - Exploratory Data Analysis on UCW External Research Funding Dataset
The primary aim of this project is to conduct an exploratory data analysis (EDA) on the UCW External Research Funding dataset to identify trends, correlations, and insights into the allocation and impact of research funding. By examining variables such as funding amounts, departmental distribution, project duration, and funding sources, we seek to understand the factors that influence the success and efficiency of funded projects at the University Canada West. This analysis will help highlight areas of strength and opportunities for improvement in the management and utilization of research grants.
# Dataset
**Funding Approved**
This dataset includes detailed information about research projects that have received funding approval at the University Canada West. Key attributes include:
- Application ID: A unique identifier for each funding application.
- Approval Date: The date when the funding was approved.
- Department: The academic department where the research is conducted.
- PI Name: Name of the Principal Investigator leading the research.
- Funding Source: The agency or organization providing the funding.
- Approved Amount: The amount of funding approved for the project.
- Project Start Date: The start date of the research project.
- Project End Date: The anticipated end date of the research project.
- Expected Outcomes: Expected results or impact of the research.
- Funding Status: Current status of the project (e.g., Active, Completed).
  # 
**Funding Agency Report**
This dataset encompasses applications submitted for research funding, detailing the review and approval process. Key attributes include:
- Application ID: A unique identifier matching with the 'Funding Approved' dataset.
- Project Title: The title of the research project.
- Researcher Name: Name of the researcher applying for funding.
- Department: The academic department of the researcher.
- Submission Date: The date on which the funding application was submitted.
- Review Date: The date when the application was reviewed.
- Funding Requested: Total amount of funding requested in the application.
- Approval Status: Status of the application (e.g., Approved, Pending, Rejected).
- Similar Past Proposals: Number of similar proposals submitted in the past.
- Past Approval Rate: Approval rate for similar past proposals.
# Methodology
1. Data Storage and Ingestion
- Storage Design: Designed an efficient data storage solution using AWS S3 for scalability and accessibility.
- Dataset Preparation: Loaded the datasets into structured formats suitable for analysis using AWS DataBrew and AWS Glue.
- Data Ingestion: Ingested data into AWS S3, maintaining data integrity and security.  
![Data Storage and Ingestion](https://github.com/PSreeti/cloudcomputing-AWS-preeti/blob/main/Step1.png)
2. Data Processing
- Pipeline Design: Designed data pipelines using AWS Glue to automate data processing from ingestion to storage.
![Pipeline Design](https://github.com/PSreeti/cloudcomputing-AWS-preeti/blob/main/ETLWeek%233.drawio%20(1).png)
- Data Cleaning: Handled inconsistencies, missing values, and errors.
- Data Structuring: Structured the cleaned data to meet analytical requirements.
 ![Data Structuring](https://github.com/PSreeti/cloudcomputing-AWS-preeti/blob/main/Screenshot%201.png)
- Pipeline Implementation: Automated the data flow through the implemented pipelines.
![Pipeline Implementation](https://github.com/PSreeti/cloudcomputing-AWS-preeti/blob/main/ETL_AWS.png)
3 Data Analysis and Visualization
-	Data Analysis: Utilized AWS Glue and other analytical tools to perform deep analysis and uncover insights and trends.
-	Data : Created graphs and charts using AWS QuickSight to visualize the results clearly and informatively.
![Data Visualization](https://github.com/PSreeti/cloudcomputing-AWS-preeti/blob/main/Week4.png)
4 Data Management and Monitoring
- Data Publishing: Made findings and visualizations accessible to stakeholders and decision-makers.
![Data Publishing](https://github.com/PSreeti/cloudcomputing-AWS-preeti/blob/main/Webserver-2.png)
- Data Protection: Ensured data privacy and compliance with relevant regulations.
![Data Repliation](https://github.com/PSreeti/cloudcomputing-AWS-preeti/blob/main/Screenshot2.png)
- Data Governance: Managed data access, auditing, and quality.
- Data Monitoring: Monitored the performance and health of data operations using AWS CloudWatch.
![Data Plotting](https://github.com/PSreeti/cloudcomputing-AWS-preeti/blob/main/Monitoring%26ControllingDashboard-2.png)

# Tools and Technologies
**AWS Services**
- AWS S3: Used for scalable and secure data storage.
- AWS DataBrew: Utilized for preprocessing tasks to structure the datasets.
- AWS Glue: Employed for data integration, cleaning, and pipeline execution.
- Amazon Athena: Used for performing interactive queries directly on data stored in Amazon S3 using standard SQL
- AWS QuickSight: Used for creating intuitive and informative data visualizations.
- Amazon EC2: For publishing data
- AWS CloudWatch: Leveraged for monitoring the performance and health of data operations.
# Deliverables:
**Data Visualizations** - A series of detailed visualizations created using AWS QuickSight, which serve as the primary method for communicating the findings from the analysis of the UCW External Research Funding dataset. These visualizations effectively illustrate key insights such as the distribution of funding across departments, trends over time, and correlations between funding amounts and research outcomes. Each visualization is designed to be both informative and accessible, making complex data understandable at a glance.


# Project 2 - Descriptive Analysis on Employees salary Department wise
The primary aim of this project is to conduct a Descriptive Analysis on the Employee Remuneration and Expenses dataset to identify trends and insights related to minimum salaries across various departments. By examining variables such as salary distribution, departmental categories, and year, we seek to understand the underlying factors that influence salary structures within the organization. This analysis will allow us to highlight disparities, if any, in salary allocation among different departments and suggest areas for improvement in salary equity and departmental budgeting. The findings from this study will be crucial for informing human resources and financial planning strategies, aiming to enhance fairness and operational efficiency in salary management.

# Dataset
This dataset contains detailed information about employees whose earnings exceeded $75,000 in 2023, as reported by the organization. The key attributes of the dataset include:
•	Year: The year of the data record, indicating when the remuneration and expenses were reported.
•	Name: The name of the employee.
•	Department: The department where the employee works. This field is crucial for department-wise analysis of salary and expenses.
•	Title: The job title of the employee, which may correlate with their level of remuneration.
•	Remuneration: The total annual remuneration received by the employee, encompassing all forms of monetary compensation.
•	Expenses: Any reimbursed expenses that the employee claimed over the year.

# Methodology
1. Data Storage and Ingestion
- Storage Design: Designed an efficient data storage solution using AWS S3 for scalability and accessibility.
![Data Storage Design](https://github.com/PSreeti/cloudcomputing-AWS-preeti/blob/main/Picture1.png)
- Dataset Preparation: Loaded the datasets into structured formats suitable for analysis using AWS DataBrew and AWS Glue.
- Data Ingestion: Ingested data into AWS S3, maintaining data integrity and security.
  
![Data Storage and Ingestion](https://github.com/PSreeti/cloudcomputing-AWS-preeti/blob/main/Picture2.png)
2. Data Processing
- Pipeline Design: Designed data pipelines using AWS Glue to automate data processing from ingestion to storage.
![Pipeline Design](https://github.com/PSreeti/cloudcomputing-AWS-preeti/blob/main/Picture3.png)
![Pipeline Design2](https://github.com/PSreeti/cloudcomputing-AWS-preeti/blob/main/Picture4.png)
- Data Cleaning: Handled inconsistencies, missing values, and errors.
 ![Data Cleaning](https://github.com/PSreeti/cloudcomputing-AWS-preeti/blob/main/Picture5.png)
- Data Structuring: Structured the cleaned data to meet analytical requirements.
 ![Data Structuring](https://github.com/PSreeti/cloudcomputing-AWS-preeti/blob/main/Picture6.png)
- Pipeline Implementation: Automated the data flow through the implemented pipelines.
![Pipeline Implementation](https://github.com/PSreeti/cloudcomputing-AWS-preeti/blob/main/Picture7.png)
3. Data Analysis and Visualization
-	Data Analysis: Utilized AWS Glue and other analytical tools to perform deep analysis and uncover insights and trends.
-	Data : Created graphs and charts using AWS QuickSight to visualize the results clearly and informatively.
![Data Visualization](https://github.com/PSreeti/cloudcomputing-AWS-preeti/blob/main/Picture8.png)
![Data Visualization](https://github.com/PSreeti/cloudcomputing-AWS-preeti/blob/main/Picture9.png)

4. Data Management and Monitoring
- Data Publishing: Made findings and visualizations accessible to stakeholders and decision-makers.
![Data Publishing](https://github.com/PSreeti/cloudcomputing-AWS-preeti/blob/main/Picture11.png)
![Data Publishing](https://github.com/PSreeti/cloudcomputing-AWS-preeti/blob/main/Picture12.png)
- Data Protection: Ensured data privacy and compliance with relevant regulations.
![Data Repliation]g)
- Data Governance: Managed data access, auditing, and quality.
- Data Monitoring: Monitored the performance and health of data operations using AWS CloudWatch.
![Data Plotting]()

# Tools and Technologies
**AWS Services**
- AWS S3: Used for scalable and secure data storage.
- AWS DataBrew: Utilized for preprocessing tasks to structure the datasets.
- AWS Glue: Employed for data integration, cleaning, and pipeline execution.
- Amazon Athena: Used for performing interactive queries directly on data stored in Amazon S3 using standard SQL
- AWS QuickSight: Used for creating intuitive and informative data visualizations.
- Amazon EC2: For publishing data
- AWS CloudWatch: Leveraged for monitoring the performance and health of data operations.
# Deliverables:
**Data Visualizations** - A series of detailed visualizations created using AWS QuickSight, which serve as the primary method for communicating the findings from the analysis of the UCW External Research Funding dataset. These visualizations effectively illustrate key insights such as the distribution of funding across departments, trends over time, and correlations between funding amounts and research outcomes. Each visualization is designed to be both informative and accessible, making complex data understandable at a glance.

