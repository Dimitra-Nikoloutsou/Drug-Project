# Drug-Project

<h2>About Data</h2>

This project was taken from <a href="https://www.kaggle.com/datasets/prathamtripathi/drug-classification">Kaggle</a>  under the <a href="https://creativecommons.org/publicdomain/zero/1.0/">licence</a> for SQL and Tableau practice purposes.

<h2>Business Task</h2>

<p>Blood pressure and drug relationship </p>
<p>Blood pressure and age relationship </p>
<p>Blood pressure and gender relationship</p>
<p>Relationship of Blood pressure and avg. Sodium to potassium Ration in Blood </p>
<p>Cholesterol and drug relationship </p>
<p>Cholesterol and age relationship </p>
<p>Cholesterol and gender relationship</p>

<h3>1.Ask</h3>
First step is to identify the business task. The task is to discover trends and relationships between drugs and patient's condition.

<h3>2.Prepare</h3>

The file is in .csv format. I downloaded from Kaggle and imported into MS SQL Server. 

<h3>3.Process</h3>

I checked for nulls and duplicates. I changed sex field from F and M to female and male. I also changed the name of the drug so the exploration to be easier.

<h3>4.Analyse</h3>

View <a href="https://github.com/Dimitra-Nikoloutsou/Drug-Project/blob/main/SQL">SQL File</a>

I exported it in .csv file and imported it in Tableau desktop Public.

<h3>5.Share</h3>

<a href="https://public.tableau.com/app/profile/dimitra.nikoloutsou/viz/drug_project/Dashboard1">Tableau link</a> (Interactive Dashboard)

![Dashboard 2](https://user-images.githubusercontent.com/114480002/204514379-c84b3b68-b41b-46da-9287-a26793d785d3.png)

<h1> INSIGHTS </h1>

There are 200 records of patients. 52% of them are men and 48% are women. The patients are 15 to 74 years old.

We are going to make three age groups so to have a clear picture of the analysis. 
Group A= 15-34, Group B=35-54 and Group C=55-74.

People with high blood pressure take drug A, B and Y with Y to be the most common drug.

People with low blood pressure take drug Y, C and X with Y to be the most common drug.

People with normal blood pressure take drug Y and X with X to be the most common drug.

Drug A is given only to age groups 15-34 and 35-54 to patients with high bp.

Drug B is given only to age groups 35-54 and mainly to 55-74 to patients with high bp.

Drug C is given to all age groups to patients with low bp.

Drug X is given to all age groups to patients with normal and low bp.

Drug Y is the most common for all age groups and for all bp cases. A percentage of 41.76% that took drug Y was patients with high bp, follows 32.97% of low bp and then a 25.27% with normal pressure.

It looks like Y drug works like a pressure regulator as it is given in all cases.

High Sodium to potassium Ration in Blood can cause high or low bp. Patients with normal bp tend to have lower Na to K.

Those who have normal cholesterole levels are not allowed to take drug C. Normal level patients are mostly people in the category age 35-54. Surprisingly those who have normal cholesterole levels but high blood pressure are younger people (15-34).

Those who have high cholesterole levels are mostly older people and male in majority.

There is not trend in the relationship between high cholesterole levels and high blood pressure.








