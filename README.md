# Breast Cancer Cohort Analysis

This notebook contains a simulated mock exercise using a mock dataset for a Breast Cancer cohort. 

This involves analysis using follow steps: 

1. Identifying the cohort size: Include patients that have been diagnosed with an ICD10 diagnosis code leading with C50. or Z85.. 
2. EDA to study the demographic characteristics of the study cohort (age, gender, race).
3. Exploring the medication patterns observed for the study cohort. 
4. Identifying % of patients in the study cohort have triple negative breast cancer?

## TNBC
Identifying triple-negative breast cancer (TNBC) from biomarker test results means we need to find patients who are:
- ER- (Estrogen receptor)
- PR- (Progesterone receptor)
- HER2-

Source: 'https://www.cancer.org/cancer/types/breast-cancer/understanding-a-breast-cancer-diagnosis/breast-cancer-her2-status.html'

## Dataset
We have an excel doc with 4 sheets:
1. **Patient**: Patient ID and patient demographic information
2. **Diagnosis**: Patients’ medical diagnosis records
3. **Medications**: Patients’ medication records data
4. **Biomarker**: Patients’ biomarker test data

## Key Ideas
- Make correct (justifiable) assumptions
- Clean data methodically
- Join data tables correctly
- Create good visuals to summarize and analyse findings
