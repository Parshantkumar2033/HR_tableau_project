
# **HR Tableau Dashboard**

HR manager want a comprehensive dashboard to analyze **human resources data**, providing both summary views for **high-level insights** and **detailed employee records** for in-depth analysis.

[**Live Dashboard**](https://public.tableau.com/views/HR_DashboardOverviewDemographicsIncome/HRDashboard?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## **Table of content**
- **Project Overview**
- **Problem Statement**
    - **Overview**
    - **Demographics**
    - **Income Analysis**
    - **Employee Records View**
- **Dataset**
- **Visualizations**
- **Usage**
- **Technologies Used**
- **Contributing**

## **Project Overview**

This project provides an **HR Dashboard** that visualizes key employee data such as **hiring trends**, **demographics**, **income analysis**, and **performance**. The goal is to help HR teams make data-driven decisions by providing interactive visual insights into their workforce.

## **Problem Statement**

- ### **Overview** : The Overview section should provide a snapshot of the overall HR metrics, including:
    - Display the total number of **hired** employees, **active** employees, and **terminated** employees.
    - Visualize the *total number of hired* and *terminated employees* over the **years**.
    - Present a breakdown of total employees by **department** and **job titles**.
    - Compare total employees between **headquarters (HQ)** and **branches** (*New York is the HQ.*).
    - Show the *distribution of employees by **city** and **state***.

- ### **Demographics** : The Demographics section should offer insights into the composition of the workforce, including:
    - Present the *gender ratio* in the company.
    - Visualize the distribution of employees across **age groups** and **education levels**.
    - Show the total number of employees within each **age group**.
    - Show the total number of employees within each **education level**.
    - Present the **correlation** between employees’s *educational backgrounds* and their *performance ratings*.

- ### **Income Analysis** : The income analysis section should focus on salary-related metrics, including:
    - Compare salaries across different education levels for both genders to identify any discrepancies or patterns.
    - Present how the *age correlate with the salary for employees in each department*.

- ### **Employee Records View**
    - Provide a comprehensive *list of all employees with necessary information* such as **name(Full name),** **department,** **gender,** **age,** **education,** and **salary.**
    - Users should be able to filter the list based on any of the available columns.

## **Dataset**
This dataset simulates a set of employee information typically found in HR systems, including demographics, job details, salary, performance evaluations, and attrition data. The generated data is designed to mimic real-world HR data, providing a rich dataset for analysis and visualization in Tableau.

The dataset is created with the help of [**ChatGPT prompts**](Data_and_images/prompts.txt) and [**Faker**](https://fakerjs.dev/) library.
To generate or modify the data according to your convenience [*visit*](Data_and_images/data.py).
### Install Faker
Using pip
```
pip install faker
```
Using conda
```
conda install -c conda-forge faker
```
The dataset includes employee records, categorized by:

**EmployeeID, Name, Department, Position, Gender, Age, Education Level, Salary
Hiring date, Termination date, and other relevant HR data points**

The dashboard contains some manually calculated fields also.

## **Visualizations**
The *main dahsboard* consists of Visualizations, **Overview, Demographics** and **Income**.

![Main_dashboard](Data_and_images/Main_dahsboard(vizualizations).png)

The *second dashboard* shows the **Employee Records**,

![Details_dahsboard](Data_and_images/Details_dahsboard(vizualization).png)

**The live [working dashboard](https://public.tableau.com/views/HR_DashboardOverviewDemographicsIncome/HRDashboard?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link).**

## **Usage**
- Install the [**Tableau Public/Desktop.**](https://www.tableau.com/community/public)
- Clone Repository or Download the [*raw file.*](final_dashboard_1.twbx)

## **Technologies Used**
- **Python and ChatGPT** : To generate the data and prompts.
- **Faker library**
- **Tableau**

## **Contributing**
**Parshant Kumar**

[**LinkedIn**](www.linkedin.com/in/parshant-kumariiitg)

[**Tableau Public**](https://public.tableau.com/app/profile/parshant.kumar4158)










