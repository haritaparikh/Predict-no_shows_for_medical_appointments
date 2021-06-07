# predict_no_shows_for_medical_appointments
Edvancer certification project


Resource planning is crucial for any business; it's even more so for operations struggling with resource crunch. Government-sponsored medical services are a prime example of such an operation. In almost all developing countries, there is a severe shortage of medical personnel and at the same time, not ideal living conditions for a big chunk of the population further exacerbates the need for medical attention. Governments have tried floating subsidized access to poor families to increase access to healthcare. One big problem which stops better utilization of this facility is that people make appointments but do not show up without notice. That time slot could have been given to a needier person if authorities were able to determine who is very likely to not show up and follow up appropriately. The task here is to make use of historical records to build a model for predicting a No-Show for an appointment given appointment details, medical history and demographic details of the customer.
Data Files
Medical History = medical_history.csv
Demographic Details = demographic_details.csv
Train Dataset =train.csv
Test Dataset = test_share.csv

Formal Problem Statement

Variable names are self explanatory and there is no formal data dictionary provided by the client .
The task here is to build a predictive model for predicting No-shows given the appointment details. Build model on the train dataset. Test dataset does not have a
response column.

target column = No-show

passing criteria: roc_auc score more than 0.66 (submit predicted probabilities [ not the hard classes ]).
