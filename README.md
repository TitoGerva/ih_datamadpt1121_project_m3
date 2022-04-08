# ih_datamadpt1121_project_m3

MACHINE LEARNING USING DATASET OF DIAMONDS

1. INTRODUCTION:

THIS IS A MODEL OF MACHINE LEARNING FOR A KAGGLE COMPETITION,

THE GOAL OF THIS COMPETITION WAS TO ACHIEVE THE LOW SCORE FACING OUR DATASET WITH THE KAGGLE ONE,

https://www.kaggle.com/competitions/dataptmad1121/leaderboard

2. LIBRARIES USED IN THIS EXERCISE

 - Sqlalchemy
 - Pandas
 - Sklearn
 - Pickle

3. STEPS USED TO TRAIN THE MODEL:

 - STEP 1 IMPORT DATASET

 - STEP 2 WRANGLING

 - STEP 2.1 REMOVE COLUMN CITY

 - STEP 3 CONVERT CATEGORIC VALUES INTO NUMERIC

 - STEP 3.1 COLOR BECOMES 'color-encoded'
 - STEP 3.1.1 CREATE ENCODER INDICATING ORDER OF VARIABLE (low VALUE TO high Value)
 - STEP 3.1.2 TRANSFORM VALUES IN COLUMN 'color' INTO NUMERIC VALUES IN TRAINING DATASET
 - STEP 3.1.3 TRANSFORM VALUES IN COLUMN 'color' INTO NUMERIC VALUES IN TEST DATASET

 - STEP 3.2 CUT BECOMES 'cut-encoded'
 - STEP 3.2.1 CREATE ENCODER INDICATING ORDER OF VARIABLE (low VALUE TO high Value)
 - STEP 3.2.2 TRANSFORM VALUES IN COLUMN 'cut' INTO NUMERIC VALUES IN TRAINING DATASET
 - STEP 3.2.3 TRANSFORM VALUES IN COLUMN 'cut' INTO NUMERIC VALUES IN TEST DATASET

 - STEP 3.3 CLARITY BECOMES 'clarity-encoded'
 - STEP 3.3.1 CREATE ENCODER INDICATING ORDER OF VARIABLE (low VALUE TO high Value)
 - STEP 3.3.2 TRANSFORM VALUES IN COLUMN 'clarity' INTO NUMERIC VALUES IN TRAINING DATASET
 - STEP 3.3.3 TRANSFORM VALUES IN COLUMN 'clarity' INTO NUMERIC VALUES IN TEST DATASET

 - STEP 4 DEFINE COLUMN TARGET AND FEATURES (IN OUR MODEL, ALL THE FEATURES ARE NUMERICAL)

 - STEP 5 APLY SCALER ON TRAININING MODEL

 - STEP 6 SPLIT TEST MODEL TO APPLY OUR TRAINING DATASET

 - STEP 7 SELECT A MODEL OF REGRESSION (IN THIS CASE, RANDOMFOREST IS APPLIED) AND TRAIN THE MODEL

 - STEP 8 OBTAIN RMS TO CONFIRM THE HIGH VALUE OF OUR MODEL

 - STEP 9 APPLY SCALER IN TEST DATASET

 - STEP 10 CREATE THE DATASET TO FACE KAGGLE MODEL

 - STEP 11 EXPORT DATASET INTO CSV

THANK YOU!

GERVASIO FELICIOSI




