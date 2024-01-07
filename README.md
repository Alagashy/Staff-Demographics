# FMDC ICT STAFF DEMOGRAPHICS

### Project Overview

This analysis project aims to provide insight into the diversity of staffs within the ICT department of FMDC including factors such as Gender, Age, Qualification, Post appointed, Religion and more. These factors help us to make data-driven decision and gain a deeper understanding of the demographic composition of the organization.

### Data Sources

Staff Data: The primary data source for this analysis is "FMDC ICT.xls" file, containing detailed information about the staffs of the ICT department of the organization.

### Tools
For the purpose of this project, the tool utilized is 

- Excel - It was used for the data cleaning, visualization and Report.

### Data Cleaning/Preparation
In this phase, we performed preparation task on the dataset such as
1. Loading the data and inspection to identify what dirtiness is in the data
2. Handling missing values
3. Data cleaning and Formatting ( formatted some data into their appropriate format such as the date, currency e.t.c. Also employ conditional statement and formulas to calculate some needed fields not present in the given data.

### Exploratory Data analysis

EDA was used to answer some questions like;

- What degree holders are most employed to the ICT department?
- Are the employed staffs more of a married person or single?
- The age range of the employed staffs
- What unit in the department are the staffs most deployed to?

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
1. The department is composed of a greater number of BSC degree holder totaling 45 personnel others are MSC with 1, HND holder totaling 15, OND with 3, and SSCE with 1 personnel.
2. The analysis shows we have more of females in the department than males.
3. More of Singles than the married staffs.
4. The EMR unit is the most occupied unit in the department.

### Recommendations
- A uniform deployment of staffs to other units in the department is adviced so as to achieve a well distributed workload.
