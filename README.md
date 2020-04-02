# StarbucksOffers
Datascience project evaluating Starbucks promotional offers.

All of the data analysis can be found in Starbucks_Capstone_notebook.ipynb.  In this notebook the offer effectiveness is explored and a RandomForestClassifier is used to predict how a given user will respond to a given offer.

All required python libraries can be found in requirements.txt

The data for the project can be foun in the data folder.
  - porfolio.json: information on offers
  - transcript.json: transcript of events
  - profile.json: user profile information
  
Results from the project are summarized in a short report 

Result file can be found in the results file.  These csv files were saved due to the time required to prepare them from the raw input data files.
  - c_no_v_df.csv: csv file with offers that were completed but never viewed
  - vc_df.csv: csv file with offers viewed and completed
  - received_ignored_df.csv: csv file with offers received and ignored
  - rf_rand_optimized.pkl:  pickle file with parameters for an optimized RandomForestClassifier
