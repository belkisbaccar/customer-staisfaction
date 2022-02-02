# Study-of-Clients-satisfaction
 ## Main Goal : STUDY OF CLIENTS’ SATISFACTION ABOUT MULTINATIONAL TELECOMMUNICATIONS  COMPANY
 
### Methodology : IBM Master Plan

### Data Description: the data Provided : an excel file " QoS_B2B(ORANGE)" is a Quality of Service business to business survey done by Orange in 2019 in order to study the satisfaction of its clients compared to other operators (Ooredoo and Tunisie Telecom)

### Work Done:
* Scrapping data from social networks (Twitter, Youtube, Facebook, Instagram)
* Creation of a data warehouse for internal data 
* Creation of a mongoDB database to store external data
* Creation of an arabic dectionary using NLP on external data 
* Predicting the customer satisfaction based on video , audio and comments
* Data Visualization using Internal and External Data
* Deployement of models , Dashboards and chatbot to a website 


### Tools Used :
* Python : data cleaning , scraping and modeling
* Microsoft Excel : for data understanding and data manipulation
* Rasa framework : for the chatbot creation
* Microsoft tools ( SSMS , SSIS) :  for the datawarehouse creation and data integration
* SQL server : internal data storing
* MongoDB : external data storing
* Power BI :data visualization 
* Django framework : deployement phase

### Files & directories:
* ChurnTel2 : includes the deployed project
* rasa : the chatbot 
* models : includes several models for satisfaction prediction
* External Data Preparation : presents the python files used for the external data cleaning
* Internal Data Preparation : presents the python files used for the internal data cleaning + the excel files of each step of the cleaning
* Data Visualization : includes the pdf version of the rapport done in Power bi
