# Dataset-Eventlogs

Synthetic_data.csv: This CSV file contains synthetic data generated for experimentation and testing purposes. The data is artificially created and does not represent real-world information. It serves as a simulated dataset to evaluate anonymization techinques without compromising privacy.

EventLog_without_attributes.csv: This CSV file contains the event log exported from the AnyLogic simulation model. The file does not inlcude generated patient data from the first CSV file.


Unanonymized_EventLog.csv: This CSV file contains an event log in its original, unanonymized form. It includes all attributes found in the synethic data file, the file may potentially reveal sensitive information about individuals. 

Anonymized_EventLog.csv: This CSV file contains an anonymized eventlog that has undergone the k-anonymity process. The dataset has been modified to ensure that each record is indistinguishable from at least k-2 other records with respect to quasi-identifiers. 
