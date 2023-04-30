# DM---Final-Project

A Data Mining project to build a Text classifier for Kaggle Top Reddit Posts and Comments dataset

Steps for Execution in Google Colab :

Upload the notebook using File -> Upload notebook
Follow the below steps to download the kaggle dataset for execution :
Download API Credentials from Kaggle Profile (Account -> Create New API token). A "kaggle.json" file will be downloaded.
Upload "kaggle.json" file to Google Colab.
Run the following commands in Google Colab :
! pip install kaggle
! mkdir ~/.kaggle
! cp kaggle.json ~/.kaggle/
! chmod 600 ~/.kaggle/kaggle.json
Run the command "! kaggle datasets download tushar5harma/topredditcomments" to download the dataset
Run the command "! unzip topredditcomments.zip" to unzip the file.
Run all the code cells
The above instructions are referred from "https://www.analyticsvidhya.com/blog/2021/06/how-to-load-kaggle-datasets-directly-into-google-colab/"
