# MLAI-Projects
Data Analytics , Text Processing , Feature Engineering , Image Classification, Deep Learning,Predictive Modelling

Data
The data for this case study is provided in the form of csv files. There are in total 3 files:
1. essays.csv: contains project text posted by teachers.
2. projects.csv: contains information about each project
3. outcomes.csv: contains information about the outcomes of projects
Any project posted before 2014-01-01 is in the training set (along with its funding outcomes). Any project posted after that is in the test set.

Links to data
outcomes.csv: https://s3.us-east-2.amazonaws.com/datafaculty/final_case/outcomes.csv.zip
projects.csv: https://s3.us-east-2.amazonaws.com/datafaculty/final_case/projects.csv.zip
essays.csv: https://s3.us-east-2.amazonaws.com/datafaculty/final_case/essays.csv.zip


Deliverables
Following are the submission requirements for this case study:
1. Data Audit report and code used to create the data audit report. You can find a sample data audit report in the data folder; the name of the file is sample_data_audit.csv. You will need to submit data audit report for each data set along with the code.
2. Feature engineering code in a jupyter notebook format. Make sure the code is properly commented out.
3. You will also need to submit the code for the final model selected by you, the model should be built to predict if a project is exciting.
4. AUC reported on five-fold CV done by you, using the final model selected in 3. The AUC should be reported in the following format in a csv file:
Fold, AUC
1,Value
2, Value
3,Value
4,Value
5,Value
5. Probability predictions for test data using the model finalized in 3. The predictions should also be submitted as a csv file with the following format:
is_exciting, projectid
0.08, projectid1
0.9, projectid2
