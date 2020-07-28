# Discordant Clostridioides difficile diagnostic assay and treatment practice: a cross-sectional study in a tertiary care hospital, Geneva, Switzerland 
A sample readme to match with our dataset  

## Description
To determine the proportion of patients who received a treatment for Clostridioides difficile infection (CDI) among those presenting a discordant Clostridioides difficile diagnostic assay and to identify patient characteristics associated with the decision to treat CDI. 

## List of variable 
All variables that were used in our analyses

- Gender
  - 1 = female
  - 0 = male 
  
- Age
  - Age at the time of test prescription
  
- Patient's location 
  - Patient's location at the time of test prescription (inpatient or outpatient). Inpatients are classified according to their hospitalization unit. 
  
- Outpatient
  - Patients with ambulatory care at the time of test prescription
  
- Inpatient (yes=1)
  - Hospitalized patients at the time of test prescription, or patients for whom the test was performed in the emergency department and were later hospitalized. 
  
- Age ≥ 65 yo (yes=1)
  - Age of ≥ 65 years old at the time of test prescription
  
- History of hospitalisation (yes=1)
  - History of an hospitalisation of ≥ 48 hours in the past 12 weeks before test prescription 
  
- History of C.difficile (yes=1)
  - All patients with a history of positive  C. difficile test results (NAAT+ or EIA+ or TC+) who had received a treatment for CDI 

- History of antibiotic therapy (yes=1) 
  - History of any antibiotic treatment of ≥ 48 hours in the past 12 weeks before test prescription 
  
- Ongoing treatment of proton pump inhibitor (yes=1)
  - Patients with any ongoing proton pump inhibitor treatment at the time of test prescription 

- Immunosuppression (yes=1)
  - Patients with chemotherapy within the 60 days before test prescription; SOT (solid organ transplant) patients, HSCT (hematopoietic stem cell transplant) patients, ongoing steroid treatment 
  
- Chronic kidney disease (yes=1)
  - Patient with a known chronic renal insuffisiency defined as a creatinine clearance < 60ml/min 
  
- Obesity (yes=1)
  - Patients with a body mass index ≥ 30 
  
- Diarrhea at the time of testing (yes=1)
  - patients with ≥ 3 unformed stools in 24 h. 

- Radiological exam (yes=1)
  - any abdominal radiological exam (CT-scan, PET-CT)
  
- Delay between imaging and treatment introduction (days)
  - negative value: imaging before treatment introduction
  - positive value: imaging after treatment introduction 
  
- Delay between abdominal CT scan and test result (days)
  - negative value: imaging before test result introduction
  - positive value: imaging after test result introduction
  
- Abdominal CT-scan (yes=1)

- CT-scan indication: suspicion of colitis (yes=1)
  - The suspicion of C. difficile colitis was the principal indication for abdominal CT-scan
  
- CT-scan indication: suspicion of C. difficile complication (yes=1)
  - The suspicion of C. difficile colitis complication (perforation, toxic megacolon, ileus) was the principal indication for abdominal CT-scan
  
-CT-scan indication: suspicion of abdominal infection (yes=1)
  - The suspicion of unspecified abdominal infection was the principal indication for abdominal CT-scan
  
- CT-scan indication: suspicion of urological disease (yes=1)
  - The suspicion of an urological disease was the principal indication for abdominal CT-scan
  
- CT-scan indication: oncologic disease (yes=1)
  - The suspicion of an oncologic disease was the principal indication for abdominal CT-scan
  
- CT-scan indication: suspicion of osteo-articular disease (yes=1)
  - The suspicion of an osteo-articular disease (arthritis, fracture) was the principal indication for abdominal CT-scan
  
- CT-scan results: signs of colitis (yes=1)
  - Any patient with signs of colitis visualized on abdominal CT-scan
  
- Rectosigmoidoscopy (yes=1)
  - Patient who underwent rectosigmoidoscopy 
  
- Rectosigmoidoscopy with typical signs of C. difficile (yes=1)
  - Patient who underwent rectosigmoidoscopy and who had typical C. difficile endoscopic lesions
  
- CDI severity criteria (yes=1)
  - Patient with WBC (white blood count) > 15 G/l, or serum creatinine > 133 µmol/L at the time of test prescription
  
- Complicated CDI (yes=1)
  - Patient with ileus, toxic megacolon, sepsis or hypotension.
  
- Complicated CDI (criteria)
  - Criteria for complicated CDI (ileus, toxic megacolon, sepsis, hypotension).
  
- CDI treatement (yes=1) 
  - Patients were considered as treated for CDI if they fulfilled all of the following criteria: 1) an appropriate antibiotic treatment administered for CDI according to published guidelines5 8 14; 2) treatment introduced less than 48 h before the results of tests; 3) treatment duration of  ≥10 days or still under treatment at time of death; and 4) treatment prescribed with a written decision in the EMR for CDI treatment, or without an alternative indication for its prescription. Of note, as fecal microbiota transplantation is not performed at our centre, it was not retained in the outcome definition.

- Delay between test result and treatment introduction (days)
  - negative value: treatment introduction before test result 
  - positive value: treatment introduction after test result
  
- Treatment duration (days)
  - for patients with CDI treatment AND uncomplete treatment duration   
 
- Molecule
  - For patients with CDI treatment
  
- Infectious diseases specialist consultation (yes=1)
  - Infectious diseases specialist consultation regarding treatment introduction, duration or interruption
  
- Reason for treatment duration < 10 days (death=1/other=0)
  
- Presence of an alternative diagnosis in EMR (yes=1) 
  - Patient who underwent test for C. difficile for whom another final diagnosis was retained 


## Variables removed from the original dataset 
Variables removed to protect patients' identity or for simplification purpose (not used in the final analysis)

- Date of birth
- Date of test prescription
- Date of test result
- Number of previous C. difficile testing before the start of the study
- Number of test with POS/POS results
- Number of test with NEG/- results
- Number of test with POS/NEG results
- Number of C. difficile culture 
- History of C. difficile POS/NEG (yes=1)
- History of C. difficile POS/POS (yes=1)
- Risk factor history of an inflammatory bowel disease (yes=1)
- Date of abdominal imaging
- Indication for CT-scan (text)
- Conclusion of CT-scan report (text)
- Severity criterias details (1=WBC (white blood count) > 15 G/l, 2=serum creatinine > 133 µmol/L at the time of test prescription, 3=both, 4=none)
- Date of treatment introduction
- Date of treatment interruption  
- Treatment duration of < 10 days (days)
- Treatment duration of ≥ 10 days (days)
- Reason for treatment duration < 10 days (text)
- Presence of an alternative diagnosis in EMR (text) 
