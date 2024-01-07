# FMDC ICT STAFF DEMOGRAPHICS

### Project Overview

The goal of this analysis project is to offer insights into the diversity of staff within FMDC's ICT department, considering factors such as gender, age, qualification, designation, religion, and more. Examining these factors enables data-driven decision-making and enhances our understanding of the organization's demographic composition.
<img width="794" alt="fmdc portfolio image" src="https://github.com/Alagashy/Staff-Demographics/assets/129556814/06122830-77b1-40a7-952b-1fae7f933d71">

<img width="941" alt="fmdc dirty data" src="https://github.com/Alagashy/Staff-Demographics/assets/129556814/e159a73e-645b-4951-8878-b175ee648327">

<img width="932" alt="fmdc cleaned data" src="https://github.com/Alagashy/Staff-Demographics/assets/129556814/d3e0c6e0-5133-4896-ab58-833d7312dcc9">


### Data Sources

Staff Data: The primary data source for this analysis is "FMDC ICT.xls" file, containing detailed information about the staffs of the ICT department of the organization.

### Tools
For the purpose of this project, the tool utilized is 

- Excel - It was used for the data cleaning, visualization and Report.

### Data Cleaning/Preparation
In this phase, we performed preparation task on the dataset such as
1. Loading the data and inspecting it to identify any inconsistencies or errors within the dataset.
2. Handling missing values
3. Conducting data cleaning and formatting, which involves organizing data into appropriate formats, such as dates and currencies. Additionally, utilizing conditional statements and formulas to calculate necessary fields that are not originally provided in the dataset.

### Exploratory Data analysis

EDA was used to answer some questions like;

- Which qualifications are predominantly held by staff in the ICT department?
- Is the majority of the employed staff married or single?
- What is the age range of the employed staff?
- In which unit of the department are the staff most frequently deployed?

### Data Analysis

```
=DATEDIF(C2, TODAY(), "y")
```
```
=IF(D2<=34, "Young", IF(D2>50, "Old", IF(D2<=50, "Mid Age", "No Age Found")))
```
```
=TEXT(P2, "mmm")
```
```
=TEXT(P2, "yyyy")
 ```

### Result/Findings

The insight obtained from the analysis is as follows;

1. The department comprises 45 personnel with a BSc degree, 1 personnel with an MSc degree, 15 with an HND, 3 with an OND, and 1 with an SSCE qualification.
2. The analysis indicates a higher representation of females than males in the department.
3. There is a greater number of single individuals compared to married staff.
4. The EMR unit holds the highest occupancy within the department.

### Recommendations
- It is recommended to uniformly deploy staff to other units within the department to ensure an evenly distributed workload.
- Tailor recruitment strategies to attract a more diverse pool of candidates.
- Provide professional development opportunities to bridge any skill gaps identified.
