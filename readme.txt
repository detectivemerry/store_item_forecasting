Submission folder structure:
CZ4041_MLProject_Group20

How to run ML_Project.ipynb (Using google collab):
1) Upload the submission folder onto Google Drive
2) Download train.csv and test.csv from the competition URL and place it in the data folder
3) Download US Holiday from the URL provided and place it in the data folder
4) Rename US Holiday csv to "USHolidayDates"
5) In cell 2, update this line to your google drive path (if your google drive path is different): os.chdir('/content/drive/My Drive/CZ4041_MLProject_Group20')
6) Execute and run all, you will be prompted to authenticate your google drive for access
6) Authenticate your google drive for access by following the instructions provided by google collab
7) Execute and run all again

Note: For ease of navigation and reading, please make use of the Table of Contents. The sourcecode is structured as follows:
1) Exploratory Data Analysis & Data Preparation		# Codes for the EDA we carried out
2) SAMRIMAX						                    # Codes for our SARIMAX Model
3) Random Forest					                # Codes for our Random Forest Model
4) Prophet					                    	# Codes for our Prophet Model
5) Combine with Ensemble Learning		        	# Codes for our Ensemble Learning


URL to Kaggle Competition: https://www.kaggle.com/c/demand-forecasting-kernels-only
URL to US Holiday csv: https://www.kaggle.com/donnetew/us-holiday-dates-2004-2021