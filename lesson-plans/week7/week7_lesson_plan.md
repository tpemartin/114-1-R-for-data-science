# Project Folder, Google Drive and Colab with R

## Integrated links

  - Survey link: <https://docs.google.com/forms/d/e/1FAIpQLSe9mL_nYJhCTbKrbrsbltYxN_F0ezh1f_cDga7wKmg7LPWhSw/viewform?usp=publish-editor>
  - Feedback link: <https://docs.google.com/forms/d/e/1FAIpQLSd6tz0jKIow7_YX_F1E_OU6BmLfPCSZHAo1nkZvzrs_ENnAWw/viewform?usp=pp_url&entry.1485215976=Week7>

## Objectives

  - Create a project folder by setting up a Google Drive folder  and share it with others.
  - Upload CSV files and codebooks to Google Drive.
  - Create a Colab notebook in the shared Google Drive folder.
  - How to set up R runtime in Colab.
  - How to describe project environment to AI for better assistance.

## Teaching Flow Steps

Before starting the lesson, **remind students they can ask AI for help if needed.** Below are the steps to guide students through the lesson:

  1. Ask to create a Google Drive folder and share it with anyone with the link. 
  2. Give them the following CSV file link and the source link and ask them to use our `Codebook maker AI expert`(https://gemini.google.com/gem/3cc7c9048d83) to create codebook, 
     - CSV File: https://drive.google.com/file/d/15C0e1jL1KScAPac5mMYrB5vjwt_IebA2/view?usp=sharing
     - Source link: https://www.kaggle.com/datasets/jockeroika/life-style-data
     
  3. Teach them how to upload the CSV file and codebook file to the shared Google Drive folder. Tell them this folder can be considered as their project folder. Explain that all project files should be stored in this folder for easy access and collaboration.
  4. Teach them how to create a Colab notebook in the Google Drive folder and set up an R runtime. Make sure they know how to save the notebook in the shared folder since it is part of their project.
  5. Tell them to have AI to assist them in project development better they need to describe their project to AI, which includes
   - What development environment are you using? (Google Colab with R)
   - Where are your project files located? (Google Drive folder)
   - Environment setup instructions: 1. How to mount your project folder (use system command `gdown` to mount) 2. What programming style to follow: tidyverse 
   Show them the introduction template below. 
   6. Complete the survey:
   - **Survey**: "Paste your Google Drive folder shared link"
   - **Survey**: "Paste you project environment introduction used for AI assistance"
  
  ## Introduction template

  ```
  I am using Google Colab with R as my development environment. My project files are located in a shared Google Drive folder {{insert link to the folder}}. I want to set up my environment by following these instructions:
  1. Mount my Google Drive folder using the `gdown` system command.
  2. Follow the tidyverse programming style for my R code.
  ```



