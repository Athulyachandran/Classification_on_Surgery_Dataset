### Introduction
In this project, the problem that we will be investigating is binary classification.
We will use numbers of different features (information) about patients to predict whether they will survive the first year after surgery.
The data is dedicated to classification problem related to the post-operative life expectancy in the lung cancer patients after thoracic surgery in which there are two classes class 1 - the death of patients within one year after surgery and class 2 – the patients who survive.

### Features description
ID
DGN: Diagnosis - specific combination of ICD-10 codes for primary and secondary as well multiple tumours if any (DGN3,DGN2,DGN4,DGN6,DGN5,DGN8,DGN1)
PRE4: Forced vital capacity - FVC (numeric)
PRE5: Volume that has been exhaled at the end of the first second of forced expiration - FEV1 (numeric)
PRE6: Performance status - Zubrod scale (PRZ2,PRZ1,PRZ0)
PRE7: Pain before surgery (T,F)
PRE8: Haemoptysis before surgery (T,F)
PRE9: Dyspnoea before surgery (T,F)
PRE10: Cough before surgery (T,F)
PRE11: Weakness before surgery (T,F)Pain before surgery (T,F)
PRE8: Haemoptysis before surgery (T,F)
PRE9: Dyspnoea before surgery (T,F)
PRE10: Cough before surgery (T,F)
PRE11: Weakness before surgery (T,F)
PRE14: T in clinical TNM - size of the original tumour, from OC11 (smallest) to OC14 (largest) (OC11,OC14,OC12,OC13)
PRE17: Type 2 DM - diabetes mellitus (T,F)
PRE19: MI up to 6 months (T,F)
PRE25: PAD - peripheral arterial diseases (T,F)
PRE30: Smoking (T,F)
PRE32: Asthma (T,F)
AGE: Age at surgery (numeric)
Risk1Y: 1 year survival period - (T)rue value if died (T,F)

### Data Analysis
Taking the sample or patiens done some surgery and identifying no.of people having risk after surgery and patient dont have any risk.
considering loot of features like pain,dyspnoea,cough etc in before and after surgery.
By checking the details and done basic analysis and plotted graph for beter understanding
Decision tree is ploted for better understanding,it is a grapphical representation for all possible solution
The model giving 78 percentage accuracy
#### Tools used
pandas
numpy
matplotlib
seaborn
#### conclusion
The model have 78 percentage accuracy
Acoording tothe analysis the no.of patient in class 1 is less than as compared with claas 2
so we can conclude that in this classification problem of after thoracic surgery in the more patient is survived after surgery
more than 70 percentage patients are in no risk sector after surgery and below 30 percentage patients are in high risk catecory


