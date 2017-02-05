# COMSW4111 - Introduction to Databases
Course description: The fundamentals of database design and application development using databases: entity-relationship modeling, logical design of relational databases, relational data definition and manipulation languages, SQL, XML, query processing, physical database tuning, transaction processing, security. Programming projects are required.

## Project Contributors
Names: Amir Lavi, Catherine Zhao

Uni: al3526, caz2114

Professor Alex Biliris

## Dataset descriptionkjbgk
Every year, the United States Census Bureau collects two datasets released to the public. We will be using the personal dataset from USA to collect information about education, occupation, disabilities, insurance, and location.  

__Datasets are from Link to Data__: www2.census.gov/programs-surveys/acs/data/pums/2015/1-Year/csv_pus.zip

__Data Dictionary__: https://www2.census.gov/programs-surveys/acs/tech_docs/pums/data_dict/PUMS_Data_Dictionary_2011-2015.pdf


## Project Proposal?
In the recent election, we have learned that America is heavily divided by location and income. Thus in this project, we wanted create a database that will view individual Americans. We focused on how does your location/education/disability, affect your job? By using 2015 US population data from United States Census Bureau, we are able to create a relationship that demonstrates a person's life in America. We hope to use this application to see how different aspect of your life affect their future for a career or retirement. How many people are in a field they majored in. Moreover, we aspire to determine how much minorities(such as disability, or ethnic) are affected compared to the majority.

We will do the web design option.

## Data matching(Will be updated to match)
1. Personal
  1. __SERIALNO__
  2. Gender: SEX
  3. Age: AGEP
  4. Marital Status: MAR
  5. Nativity: NATIVITY
  6. (Place of birth: POBP05)
  7. (State Code: ST)
  8. (Education attainment: SCHL(
2. Disability(NEED ID)
  1. iddis: CREATE
  2. Self-care difficulty: DDRS
  3. Hearing difficulty: DEAR
  4. Vision difficulty: DEYE
  5: Independent living difficulty: DOUT
  6. Ambulatory difficulty: DPHY
3. Location
  1. __idstate__: POBP05
  2. Locations: POBP05
4. Education
  1. __ided__: SCHL
  2. School Degree: SCHL
5. Major
  1. Major: FOD1P
6. Job
  1. __idjob__: kl
  2. Wage: WAGP
  3. Time to arrival to work: JWAP
  4: Time to departure for work: JWDP
7. Retirement
  1. __Retirement income__: RETP
  
 
  
  
  
  
