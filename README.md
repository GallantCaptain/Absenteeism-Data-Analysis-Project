# Absenteeism-Data-Analysis-Project
This project focuses mainly on cleaning &amp; pre-processing the dataset so as to hone-in on and showcase the most fundamental data analytical skills and thinking.

**Project Guide:**
* Drop the ‘ID’ column
* Split the reasons for absence into multiple dummy variables, and then group them in the following way:
  * Group 1: Columns 1 to 14
  * Group 2: Columns 15, 16, and 17
  * Group 3: Columns 18, 19, 20, and 21
  * Group 4: Columns 22 to 28
* After that, drop the ‘Reason for Absence’ column.
* Extract the month value and the day of the week from the ‘Date’ column. Then, drop the ‘Date’ column as well.
* Turn the data from the ‘Education’ column into binary data, by mapping the value of 0 to the value of 1, and the value of 1 to
the rest of the values found in this column.

The Reason for absence column contains information about the absence, which is encoded based on the International Code of Diseases (ICD). The following table represents the various encodings:

1: Certain infectious and parasitic diseases

2: Neoplasms

3: Diseases of the blood and blood-forming organs and certain disorders involving the immune mechanism

4: Endocrine, nutritional and metabolic diseases

5: Mental and behavioural disorders

6: Diseases of the nervous system

7: Diseases of the eye and adnexa

8: Diseases of the ear and mastoid process

9: Diseases of the circulatory system

10: Diseases of the respiratory system

11: Diseases of the digestive system

12: Diseases of the skin and subcutaneous tissue

13: Diseases of the musculoskeletal system and connective tissue

14: Diseases of the genitourinary system

15: Pregnancy, childbirth and the puerperium

16: Certain conditions originating in the perinatal period

17: Congenital malformations, deformations and chromosomal abnormalities

18: Symptoms, signs and abnormal clinical and laboratory findings, not elsewhere classified

19: Injury, poisoning and certain other consequences of external causes

20: External causes of morbidity and mortality

21: Factors influencing health status and contact with health services.

And 7 categories without ICD:

22: Patient follow-up

23: Medical consultation

24: Blood donation

25: Laboratory examination

26: Unjustified absence

27: Physiotherapy

28: Dental consultation

0 : Unknown
