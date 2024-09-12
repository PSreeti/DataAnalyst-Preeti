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
![Step1](https://github.com/user-attachments/assets/3b70d3ef-4f44-476e-89d2-6f1f8097d504)
2. Data Processing
- Pipeline Design: Designed data pipelines using AWS Glue to automate data processing from ingestion to storage.
![ETLWeek#3 drawio (1)](https://github.com/user-attachments/assets/d6e9d311-cc84-475e-a6f5-fa0350347f68)
- Data Cleaning: Handled inconsistencies, missing values, and errors.
- Data Structuring: Structured the cleaned data to meet analytical requirements.
![Screenshot 1](https://github.com/user-attachments/assets/d3f3be9a-324e-46f6-a5f7-34ba7623b225)
- Pipeline Implementation: Automated the data flow through the implemented pipelines.
![ETL_AWS](https://github.com/user-attachments/assets/8a558709-62f5-4d7d-8817-c63adeecfde9)
3. Data Analysis and Visualization
-	Data Analysis: Utilized AWS Glue and other analytical tools to perform deep analysis and uncover insights and trends.
-	Data : Created graphs and charts using AWS QuickSight to visualize the results clearly and informatively.
![Week4](https://github.com/user-attachments/assets/52050e48-4971-44cf-a985-598bef66d691)
4. Data Management and Monitoring
- Data Publishing: Made findings and visualizations accessible to stakeholders and decision-makers.
![Webserver-2](https://github.com/user-attachments/assets/3e740145-f6c6-4bba-bf64-ccf217e1a8b7)
- Data Protection: Ensured data privacy and compliance with relevant regulations.
![Screenshot2](https://github.com/user-attachments/assets/f06c1e83-3dd7-4eea-8547-3d41c11d8ee7)
- Data Governance: Managed data access, auditing, and quality.
- Data Monitoring: Monitored the performance and health of data operations using AWS CloudWatch.
![Monitoring ControllingDashboard-2](https://github.com/user-attachments/assets/83bec11b-ba89-4a4d-b98f-8883cd0e50c5)

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
- Year: The year of the data record, indicating when the remuneration and expenses were reported.
- Name: The name of the employee.
- Department: The department where the employee works. This field is crucial for department-wise analysis of salary and expenses.
- Title: The job title of the employee, which may correlate with their level of remuneration.
- Remuneration: The total annual remuneration received by the employee, encompassing all forms of monetary compensation.
- Expenses: Any reimbursed expenses that the employee claimed over the year.

# Methodology
1. Data Storage and Ingestion
- Storage Design: Designed an efficient data storage solution using AWS S3 for scalability and accessibility.
![Picture1](https://github.com/user-attachments/assets/e8fdd2fb-66ea-439c-8ee8-a9e00ca604eb)
- Dataset Preparation: Loaded the datasets into structured formats suitable for analysis using AWS DataBrew and AWS Glue.
- Data Ingestion: Ingested data into AWS S3, maintaining data integrity and security.
![Picture2](https://github.com/user-attachments/assets/fb777457-3114-44f6-a16e-a3df4714f823)
2. Data Processing
- Pipeline Design: Designed data pipelines using AWS Glue to automate data processing from ingestion to storage.
![Picture3](https://github.com/user-attachments/assets/ec1fdcd8-46bc-4d76-bab9-461d7e75f5c9)
![Picture4](https://github.com/user-attachments/assets/a2f36b4b-78cb-40bc-a16a-932f522638fd)
- Data Cleaning: Handled inconsistencies, missing values, and errors.
 ![Picture5](https://github.com/user-attachments/assets/f320aa06-c514-484b-b097-5ffe9e9fe1fe)
- Data Structuring: Structured the cleaned data to meet analytical requirements.
![Picture6](https://github.com/user-attachments/assets/677eaed4-8f86-4bb5-b78c-690fa6df9254)
- Pipeline Implementation: Automated the data flow through the implemented pipelines.
![Picture7](https://github.com/user-attachments/assets/b5c4b855-f611-4202-a6cc-93303acde5fe)
3. Data Analysis and Visualization
-	Data Analysis: Utilized AWS Glue and other analytical tools to perform deep analysis and uncover insights and trends.
-	Data : Created graphs and charts using AWS QuickSight to visualize the results clearly and informatively.
![Picture8](https://github.com/user-attachments/assets/36af3b92-490c-471a-8b95-22f1b0980094)
![Picture9](https://github.com/user-attachments/assets/999adf51-6780-4274-bee1-87679accd7ca)
4. Data Management and Monitoring
- Data Publishing: Made findings and visualizations accessible to stakeholders and decision-makers.
![Picture11](https://github.com/user-attachments/assets/8d0e6c7d-3094-482f-9bac-e3797260d59c)
![Picture12](https://github.com/user-attachments/assets/21c2153b-ad66-4966-8ab6-d63b8bc0d01a)
- Data Protection: Ensured data privacy and compliance with relevant regulations.
![image](https://github.com/user-attachments/assets/3f841dd4-bab2-460f-b228-955a85125432)
- Data Governance: Managed data access, auditing, and quality.
- Data Monitoring: Monitored the performance and health of data operations using AWS CloudWatch.
![image](https://github.com/user-attachments/assets/0f726303-4c36-497d-a701-03f8325cde6c)

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

