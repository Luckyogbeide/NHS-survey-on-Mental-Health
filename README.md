# Mental Health Analysis on Students

## Introduction
The NHS, in partnership with a university, conducted a comprehensive survey to evaluate the mental health and well-being of students. The primary objective was to examine the prevalence of specific mental health conditions among students and their impact on academic performance. The study focused on conditions such as schizophrenia, psychosis, and insomnia. Data collection was carried out using a structured questionnaire distributed across students from diverse academic levels and disciplines, ensuring a broad and representative understanding of the issue.

## Problem Statement
The task to be carried out are listed below;
- Assess the survey results to identify key trends in the data.
- Determine the number of students affected by schizophrenia, psychosis, and insomnia.
- Analyze how many students have sought specialized care for these conditions.
- Examine the academic impact of these ailments, particularly through CGPA analysis.
- Investigate gender-based patterns in the prevalence of these mental health issues.
- Provide insights into the severity and scope of each condition.
- Propose recommendations for interventions or improvements based on the findings.
## The exploratory Data Analysis
The datasets were extracted from an Excel file, and the following transformations were performed using the Power Query Editor:
Three setup tables (Insomnia, Psychosis and Schizophrenia) were created from the main dataset with unique id representing the status of the mental health problem.
## Modelling
A star schema was adopted in the modelling. The dimension tables are joined to the fact table on one-to-many relationship
![](datamodel.png)

## Skills/concepts demonstrated:
The following Power Bi features were incorporated
-  Bookmarking and Filtering
-  DAX and Quick measures
-  Page Navigation
-  Modelling

## Visualization
The report comprises of four(4) pages:
- Overview
- Insomnia Analysis
- Psychosis Analysis
- Schizophrenia Analysis
  
You can interact with the report:  [here](https://app.powerbi.com/view?r=eyJrIjoiMmU1YTU1ODktOTFiNy00MGVkLTgwYjctNzcwNThkZDI5ZjUyIiwidCI6ImYzMzNmMDE4LWE3OTYtNGQ5Yy1iNmM4LThmY2RmYzAyNzEwYiJ9)

### Overview 
The page summarises the findings
![overview](overview.png)

### Insomnia report
The page gives insight into Insomnia mental health
![](Insomnia.png)

### Psychosis report
The page gives insight into the survey carried on Psychosis mental health
![](psychosis.png)

### Schizophrenia report
The page gives insight into the survey carried on Schizophrenia mental health
![](Schizophrenia.png)

### Findings


