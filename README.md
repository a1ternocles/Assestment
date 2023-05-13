# Assestment
This assesment was done with the objective to complete the 'Data Engineer and Reporting Supervisor, Project'. 

  
  On it, exercise was about to complete 6 taskes in order to create a professional Data Base using tools like 'Python',
'SQL' & 'Google APIs'. And completing the data base product using tools as 'Looker Data Studio' & 'Tableau' to give full body
for the analytics of a BPO.  

  First, a random data base on google sheets was created using https://www.mockaroo.com/ taking in mind BPOs KPIs as:
      *date           *country
      *interactions   *team_lead
      *channel        *status
      *csat           *coaching
      *service_level  *work_hours
      *cpc            *abs_hours
      *id
      *full_name
      *email
  
  It is important to highlight main KPIs from BPO suggested, these are:
      *As fictitious company, name chosen was: #CAT CHOOSE
      *Coaching completion for Agents
      *Service level %
      *Channels : Voice, Chat & Email
      *Targets:
          -Coaching 100%
          -Service Level 85%
          -CSAT 85%
  
  An Squema for a DATA WAREHOUSE was attached to this file.

  In order to show (step by step) how to create a script on python
  that help us to automatize the collection, cleaning and export of the data needed.

  It was used different libraries in order to have the script completed. List below:
      * import gspread
          from gspread_dataframe import set_with_dataframe
      * import pandas as pd
      * import mysql.connector as sql
      * import sqlalchemy as sa
      * from sqlalchemy import create_engine

  It is necessary to install these libraries by doing following:
      Into py terminal, type:
          * pip install gspread
          * pip install gspread_dataframe
          * pip install pandas
          * pip install mysql-connector-python
          * pip install sqlalchemy

  Google API's was enabled in order to get access and permissions to use Google SpreadSheets and its functions (json keys used)
  SQL WorkBench was used for the purpose of the exercise

  OPS Dashboard Suite: https://lookerstudio.google.com/reporting/4a5eaaa1-d6de-40b4-bbeb-45a915e161b8
  Executive Dashboard Suite: 

