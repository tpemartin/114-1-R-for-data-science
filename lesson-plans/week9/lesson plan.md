# Colab with R Project Environment Setup

We are going to learn how to use Colab to do programming with R language with AI's help.

## Objectives

  - Understand Colab basics and R runtime setup.
  - Know how to get file links from Google Drive.
  - Know how to download files from Google Drive in Colab.

### Working with Two Gemini's:

There are two kinds of Gemini that you can use:
1. Independent Gemini: You can use it to ask questions and get answers. (For more general planning purposes, like what data exploration to do, what models to try, etc.)
2. Integrated Gemini: You can use it inside Colab to help you write code. (For more specific coding tasks that are attached to your general planning.)
In other words, you use independent Gemini for high-level planning and Integrated Gemini for low-level coding.

#### Introduce Yourself to High-level Planning Gemini

High-level planning requires knowing your project environment, so you can describe it to Gemini. 
  - What IDE are you using? (Colab with R). 
  - (If you already know the dataset you want to explore,) The codebook of the data that you are using.

```
You are a data exploration expert on R language of tidyverse style. Your assistance follows those listed under **Rules**.

## **Rules**. 
  - Don't give code snippets unless specifically asked for.
  - Pretend that you are using Google Colab with R as your IDE where the **Files** of Colab are empty to begin with.  
  - Always follow the tidyverse programming style.
   - When make function call, always follow the format `{{package_name}}::{{function_name}}()`. Hence no need to import packages at the start of the code.
  - Don't install packages unless the user specifically asks for it.
  - When dealing with external files, always teach user how to download them into Colab's **Files** before importing them. 
```

For high-level planning, after your self-introduction and hand in your codebook of the dataset of interest, you can ask questions like:
  - "How to download dataset from {{google_drive_file_link}} into Colab using program?"
  - "How to import that dataset into R?"
  - "Where should I start for dataset exploration?"

#### Introduce Yourself to Low-level Coding Gemini

Low-level coding requires knowing how to set up your project environment in Colab.
  - What language are you using? (R)
  - Where is your data file located? (to be uploaded to Google Drive)
  - Where to save your interim results? (where is your project folder located?)
  
```
You are a coding expert on R language of tidyverse style. Your assistance follows those rules under **Rules**.

## **Rules**. 
  - Always code with R in tidyverse style.
  - When make function call, always follow the format `{{package_name}}::{{function_name}}()`. Hence no need to import packages at the start of the code.  
  - Don't install packages unless the user specifically asks for it.
```


  
## Teaching Flow Steps

1. Describe your project setup:
   1. Where is your project folder located? (Google Drive)
   2. What development environment are you using? (Colab with R)
