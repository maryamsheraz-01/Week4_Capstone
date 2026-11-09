# Week 4 Capstone: Predicting Internship Selection Outcomes
Predicts whether an applicant is likely to be selected using simple application features.

## Objective
Explore which application factors are associated with selection, and explain the results to a non-technical audience.

## Dataset
300 simulated applicants. All data is simulated, including the 4 new features (skills listed, portfolio, prior hackathon, statement quality) and the selection outcome. np.random.seed(42) makes it reproducible. Real data would be needed before any real use.

## Method
Create data, convert Yes/No to 0/1, one-hot encode Domain, remove "Under Review" rows (270 left), 80/20 split (54 test rows), Logistic Regression, evaluation.

## Key Results
Accuracy: 90.74%, Precision: 92.59%, Recall: 89.29% on the test set. The strongest factor was having a portfolio/GitHub link. Results are illustrative because the data is small and simulated.

## How to run
Open the notebook in Google Colab and run all cells top to bottom.

## Walkthrough video
https://drive.google.com/file/d/1jkqISc1qCamG2qGjONfKR6VNR2xXJCh_/view?usp=drivesdk
