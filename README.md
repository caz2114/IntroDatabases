# COMSW4111 - Introduction to Databases
Course description: The fundamentals of database design and application development using databases: entity-relationship modeling, logical design of relational databases, relational data definition and manipulation languages, SQL, XML, query processing, physical database tuning, transaction processing, security. Programming projects are required.

## Dataset description
Every year, the United States Census Bureau collects two datasets released to the public. We will be using the personal dataset from NY to collect information such as education.  

## Datasets are from Link to Data 
1. www2.census.gov/programs-surveys/acs/data/pums/2015/1-Year/csv_pusa.zip
2. www2.census.gov/programs-surveys/acs/data/pums/2015/1-Year/csv_husa.zip

## Data Dictionary
https://www2.census.gov/programs-surveys/acs/tech_docs/pums/data_dict/PUMS_Data_Dictionary_2011-2015.pdf

## Project Proposal?
  We are creating a "mapping people" application which is intended to map people's behaviors and everyday life. We are connecting several aspects of everyday life suhc as job/industry, educational level, and wheather they flush the toilet or not. Connecting this with aspects such as when they arrive to work, what major they had in college, and where they are from we would try to accomplish a borader sense of ***********.

## Expanation of the project:
  Since we have a large database in our hands, we are planning to expand our database. Our eventual goal is to have the ability to connect individual people to household data to analyze how household dynamics. If we have no mapping strategy between personal and household data we will continue to expand on personal data.
     i. Figure out how to make a relationship set on Household(?) and connect it to personal somehow(?)
     ii. Think of where people buy their clothes (try to think of a way to link socio-economic status to location or another aspect) 

## Data matching
1. Personal
  i. __SERIALNO__
  ii. Gender: SEX
  iii. Age: AGEP
  iv: Marital Status: MAR
  v:  Nativity: NATIVITY
  (vi) Place of birth: POBP05
  (vii)  State Code: ST
  (viii) Education attainment: SCHL
2. Disability(NEED ID)
  i. iddis: CREATE
  ii. Self-care difficulty: DDRS
  iii. Hearing difficulty: DEAR
  iv. Vision difficulty: DEYE
  v: Independent living difficulty: DOUT
  vi. Ambulatory difficulty: DPHY
3. Location
  i. __idstate__: POBP05
  ii. Locations: POBP05
4. Education
  i. __ided__: SCHL
  ii. School Degree: SCHL
5. Major
  i. Major: FOD1P
6. Job
  i. idjob: 
  ii. Wage: WAGP
  iii. Time to arrival to work: JWAP
  iv: Time to departure for work: JWDP
7. Retirement
  ii. __Retirement income__: RETP
  
 
  
  
  
  
