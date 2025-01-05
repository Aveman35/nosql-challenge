# nosql-challenge
This repository contains the following files and folders:

Resources Folder
- The Resources Folder contains the establishments.json file which houses all the data for analysis
  
NoSQL_setup_starter.ipynb
- This Jupyter Notebook contains the code for creating in MongoDB, the database `uk_food` and the collection `establishments`. The file further updates, and modifies documents within the `establishments` collection
- Import the dataset by running in the Terminal using git bash: `mongoimport --type json -d uk_food -c establishments --drop --jsonArray establishments.json`

NoSQL_analysis_starter.ipynb

- This Jupyter Notebook contains the code for analysis, sorting, and answering the challenge questions
