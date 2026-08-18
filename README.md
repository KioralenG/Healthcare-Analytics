# Hospital Analytics: Data Analysis for Healthcare Operational Decision-Making

Hospitals generate thousands of records every day, including patient admissions, medical consultations, diagnoses and prescribed medications. Transforming this information into actionable insights is essential for improving operational efficiency, optimizing resource allocation and supporting strategic decision-making.

This project develops an end-to-end healthcare analytics workflow using Python to integrate multiple datasets, perform data cleaning, exploratory analysis, KPI generation, database integration with SQLite and visualizations focused on hospital management.

*** Business Problem:

Hospital administrators need reliable information to understand:

1. Which diseases require the highest waiting time.
2. Which specialties consume the largest budget.
3. Which medicines are prescribed most frequently.
4. Which patient groups require more medical attention.


*** Objectives:
1. Identify trends in consultations.
2. Calculate KPIs
3. Optimize hospital resource allocation.
4. Identify the most common diagnoses and prescribed treatments.

The objective of this project is to transform raw hospital data into actionable insights that support operational decision-making.

*** Architecture:

```text
CSV Files
    │
    ▼
Data Cleaning
    │
    ▼
Pandas DataFrames
    │
    ▼
SQLite Database
    │
    ▼
Data Analysis
    │
    ▼
Visualizations
    │
    ▼
REST API
```

*** Datasets:
1. Consultations
2. Diagnoses
3. Medications
4. Patients

*** Technologies:
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SQLite
- SQLAlchemy
- Flask

*** Methodology:

1. Data collection
2. Data cleaning
3. Missing value treatment
4. Data integration
5. Database migration using SQLite
6. Exploratory Data Analysis (EDA)
7. KPI calculation
8. Data visualization
9. REST API development

*** KPIs:
1. Total Patients
2. Total Cost
3. Average Waiting Time
4. Total Consultations
5. Average Consult Cost
6. Average Age

*** Main Findings:
1. Hypertension presents both the highest average waiting time and the highest average treatment cost, while Dengue shows the lowest values in both indicators.
2. Senior citizens experience the longest average consultation waiting time among all age groups.
3. Pulmonology is the specialty with a higher waiting time
4. Internal Medicine represents the highest total treatment cost among all medical specialties.
5. Adults have a higher treatment cost, being 50% higher than senior citizens
6. A significant proportion of patients present multiple diagnoses, increasing consultation frequency and overall treatment costs.
7. Metformin is the most used medicine, whereas Paracetamol is the less used medicine

*** Recommendations:
1. Optimize specialist allocation for Hypertension management.
Patients diagnosed with Hypertension experience the highest average waiting time and treatment cost. Evaluating specialist availability and consultation scheduling may help reduce waiting times while improving patient outcomes.
2. Review operational efficiency within Pulmonology.
Since Pulmonology presents the longest average waiting time among all specialties, further analysis should be conducted to identify potential bottlenecks, such as staffing levels, consultation duration or appointment scheduling.
3. Implement preventive care and patient follow-up programs.
A considerable number of patients present multiple diagnoses, which may increase consultation frequency, treatment complexity and healthcare costs. Preventive campaigns and continuous follow-up could improve treatment adherence and reduce hospital demand.
4. Strengthen medication inventory management.
Metformin is the most frequently prescribed medication in the dataset. Maintaining adequate inventory levels and monitoring stock availability can help prevent shortages and ensure uninterrupted patient care.
5. Use predictive analytics for resource planning.
As a future improvement, predictive models could be developed to estimate patient demand, identify disease trends and forecast medication consumption, enabling more efficient planning of hospital resources and budgets.

*** Lesson Learned:
1. The analysis demonstrates how integrating multiple healthcare datasets can generate valuable insights for hospital management. Beyond identifying trends, combining patient, consultation, diagnosis and medication information allows healthcare organizations to optimize resource allocation, improve operational efficiency and support data-driven decision-making.

*** Future Improvements

1. Deploy the REST API to the cloud.
2. Develop an interactive Power BI dashboard.
3. Integrate real-time hospital data.
4. Apply Machine Learning models to predict patient demand and waiting times.
5. Automate data ingestion using Apache Airflow.

Top 10 Diagnosis
<img width="886" height="656" alt="image" src="https://github.com/user-attachments/assets/b6e84228-07a2-4483-aabd-f17aaaa22873" />

Average waiting time per diagnosis
<img width="886" height="656" alt="image" src="https://github.com/user-attachments/assets/323f7f8b-9627-4451-8c81-52d456bfa071" />

Average Waiting time per Age Group
<img width="861" height="820" alt="image" src="https://github.com/user-attachments/assets/61127e16-d1d8-4d8e-ac53-1281a4db663d" />

Waiting time in minutes per specialty
<img width="886" height="628" alt="image" src="https://github.com/user-attachments/assets/5223b535-aafd-42c1-a736-6e434dff1d5d" />

Diagnosis Average Cost
<img width="886" height="656" alt="image" src="https://github.com/user-attachments/assets/55c1ed45-f390-417b-bacc-56828a9090ae" />

Total Specialty Cost(MXN)
<img width="886" height="798" alt="image" src="https://github.com/user-attachments/assets/58788c29-796b-4262-8590-6f97f2ef3703" />

Age Group Cost percentage
<img width="733" height="638" alt="image" src="https://github.com/user-attachments/assets/160b7c5a-7ffc-4b67-8ba6-7de0672db278" />

Patients with more than 1 diagnosis
<img width="870" height="760" alt="image" src="https://github.com/user-attachments/assets/69e4234c-227d-49d5-bcd0-8617c74b678d" />

Medication Usage
<img width="886" height="656" alt="image" src="https://github.com/user-attachments/assets/b3eca81e-c1b8-452e-9eef-2a3e992429b6" />

Medication Usage per diagnosis
<img width="886" height="711" alt="image" src="https://github.com/user-attachments/assets/eacc503d-59d0-4ace-9177-d7afdbc15aa6" />

Medication Cost
<img width="886" height="767" alt="image" src="https://github.com/user-attachments/assets/92a557f8-212c-43a9-a976-1a93cab7691d" />

