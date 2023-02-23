# Healthcare_Provider_Fraud_Detection

<b> Healthcare fraud types by providers are: </b> 

Billing for services that were not provided.
Duplicate submission of a claim for the same service.
Misrepresenting the service provided.
Charging for a more complex or expensive service than was actually provided.
Billing for a covered service when the service actually provided was not covered.
The datasets consists of

<b> Train.csv and test.csv-</b> 

This file consists of Provider Data , Inpatient Data, Outpatient Data, Beneficiary Details Data and various categorical features and also the PotentialFraud which we have to predict.

<b> Provider Data </b> 

This data provides insights of Provider Id , PotentialFraud mark on that ids. we have to predict PotentialFraud for future data.

<b> Inpatient Data </b> 

This data provides insights about the claims filed for those patients who are admitted in the hospitals. It also provides additional details like their admission and discharge dates and admit d diagnosis code.

<b> Outpatient Data </b> 

This data provides details about the claims filed for those patients who visit hospitals and not admitted in it.

<b> Beneficiary Details Data </b> 

This data contains beneficiary KYC details like DOB, DOD, Gender, Race, health conditions (Chronic disease if any), State, Country they belong to etc.


The goal of this project is to " predict the potentially fraudulent providers " based on the claims filed by them.along with this, we will also discover important variables helpful in detecting the behaviour of potentially fraud providers. This is basically a classification problem.
