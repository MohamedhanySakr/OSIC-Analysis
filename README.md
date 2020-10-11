# OSIC-Analysis
# OSIC Pulmonary Fibrosis Progression
#### Predict lung function decline
OSIC stand for Open Source Imaging Consortium
OSIC is a not-for-profit, co-operative effort between academia, industry and philanthropy. The group enables rapid advances in the fight against Idiopathic Pulmonary Fibrosis (IPF), fibrosing interstitial lung diseases (ILDs), and other respiratory diseases, including emphysematous conditions. Its mission is to bring together radiologists, clinicians and computational scientists from around the world to improve imaging-based treatments.

Imagine one day, your breathing became consistently labored and shallow. Months later you were finally diagnosed with pulmonary fibrosis, a disorder with no known cause and no known cure, created by scarring of the lungs. If that happened to you, you would want to know your prognosis. That’s where a troubling disease becomes frightening for the patient: outcomes can range from long-term stability to rapid deterioration, but doctors aren’t easily able to tell where an individual may fall on that spectrum. Your help, and data science, may be able to aid in this prediction, which would dramatically help both patients and clinicians.

### In this repo i will show you analysis for the OSIC kaggle competition data
# First
## I used google colab in this project as it provide a free GPU 
## I used Kaggle API to get the dataset on my Colab Notebook

## Data is so big so you can download it from the link below
https://www.kaggle.com/c/osic-pulmonary-fibrosis-progression/data

# Data 
## Files
This is a synchronous rerun code competition. The provided test set is a small representative set of files (copied from the training set) to demonstrate the format of the private test set. When you submit your notebook, Kaggle will rerun your code on the test set, which contains unseen images.

1. train.csv - the training set, contains full history of clinical information
2. test.csv - the test set, contains only the baseline measurement
3. train/ - contains the training patients' baseline CT scan in DICOM format
4. test/ - contains the test patients' baseline CT scan in DICOM format
5. sample_submission.csv - demonstrates the submission format

## Columns
train.csv and test.csv
1. Patient- a unique Id for each patient (also the name of the patient's DICOM folder)
2. Weeks- the relative number of weeks pre/post the baseline CT (may be negative)
3. FVC - the recorded lung capacity in ml
4. Percent- a computed field which approximates the patient's FVC as a percent of the typical FVC for a person of similar characteristics
5. Age
6. Sex
7. SmokingStatus

### After this analysis you can apply machine learning algorithms to predict some insights 
