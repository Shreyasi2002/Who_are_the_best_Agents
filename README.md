*Your client is a Financial Distribution company. Over the last 10 years, they have created an offline distribution channel across the country. They sell Financial products to consumers by hiring agents in their network. These agents are freelancers and get a commission when they make a product sale.*


## *Overview of your client On-boarding process*
*Managers at your client are primarily responsible for recruiting agents. Once a manager has identified a potential applicant, they would explain the business opportunity to the agent. Once the agent provides the consent, an application is made to your client to become an agent. This date is known as application_receipt_date.*

*In the next 3 months, this potential agent has to undergo a 7 days training at your client's branch (about Sales processes and various products) and clear a subsequent examination in order to become an agent.*


## *The problem - Who are the best agents?*
*As is obvious in the above process, there is a significant investment which your client makes in identifying, training and recruiting these agents. However, there are a set of agents who do not bring in the expected resultant business after recruitment.*

*Your client is looking for help from data scientists like you to help them provide insights upfront using their past recruitment data. They want to predict whether an agent will source new business in the next 3 months which would help them identify the right agents to hire and thus make the whole process more agile.*


## *Data*
***Train**: It contains training data for all past recruitments along with the target variable which is 1 if the agent was able to source business within 3 months of recruitment and 0 otherwise*

| *Variable* | *Definition* |
| --- | --- |
| *ID* | *Unique Application ID* |
| *Office_PIN* | *PINCODE of Your client's Offices* |
| *Application_Receipt_Date* | *Date of Application* |
| *Applicant_City_PIN* | *PINCODE of Applicant Address* |
| *Applicant_Gender* | *Applicant's Gender* |
| *Applicant_BirthDate*	| *Applicant's Birthdate* |
| *Applicant_Marital_Status* | *Applicant's Marital Status* |
| *Applicant_Occupation* | *Applicant's Occupation* |
| *Applicant_Qualification* | *Applicant's Educational Qualification* |
| *Manager_DOJ* |	*Manager's Date of Joining* |
| *Manager_Joining_Designation*	| *Manager's Joining Designation* |
| *Manager_Current_Designation*	| *Manager's Designation at the time of application sourcing* |
| *Manager_Grade*	| *Manager's Grade* |
| *Manager_Status* | *Current Employment Status (Probation / Confirmation)* |
| *Manager_Gender* | *Manager's Gender* |
| *Manager_DoB*	| *Manager's Birthdate* |
| *Manager_Num_Application*	| *No. of Applications sourced in last 3 months by the Manager* |
| *Manager_Num_Coded*	| *No. of agents recruited by the manager in last 3 months* |
| *Manager_Business* | *Amount of business sourced by the manager in last 3 months* |
| *Manager_Num_Products* | *Number of products sold by the manager in last 3 months* |
| *Manager_Business2*	| *Amount of business sourced by the manager in last 3 months excluding business from their Category A advisor* |
| *Manager_Num_Products2*	| *Number of products sold by the manager in last 3 months excluding business from their Category A advisor* |
| *Business_Sourced(Target)* | *Business sourced by applicant within 3 months [1/0] of recruitment* |


***Test**: It contains information regarding all the agents for whom the participant is expected to predict the probability of an agent sourcing business within 3 months of recruitment*
