# SEN1221- Statistical Analysis of Choice Behaviour

## 1. Introduction

Welcome to the repository for the SEN1221 course on Statistical Analysis of Choice Behaviour. This ReadMe file contains all the essential information and instructions for the course. Here, you will find materials for lab sessions 1, 2, and 3, along with their respective databases. Please review the following information carefully.

If you are not familiar with Python, we recommend completing lab session 0, which provides the necessary tools covered in a core Python course. This knowledge will enable you to follow lab sessions 1 to 3, covering topics such as data structures, utilising external libraries, data exploration, visualization, etc. Additionally, it will help you set up and become acquainted with the coding environment (see [this link] to prepare your environment).

## 2. Description

Discrete Choice Models (DCMs) have been widely employed to study the decision-making behaviour of individuals across various scientific domains, including transportation, marketing, and health, among others. DCMs are particularly used to infer preferences over attributes and alternatives, forecast demand, and predict the impact of new policies.

This course aims to equip students in the socio-technical domain with a comprehensive understanding of DCMs. It prepares students to formulate hypotheses, develop diverse models, and generate solutions for the challenges our society faces in their future careers. 

The course consists of oral lectures and lab sessions. While attendance at lectures and lab sessions is highly recommended to keep up with the course, it is not mandatory.

## Lab sessions
Lab sessions aim to demonstrate and reinforce knowledge about different discrete choice models, the underlying assumptions, estimation techniques, and how to interpret model outcomes. They provide students with hands-on experience in discrete choice modelling. The lab sessions include a series of exercises in the form of Jupyter notebooks. 

`Lab session 1` introduces discrete choice models, focusing specifically on the Multinomial Logit (MNL) model based on random utility theory. Students will acquire the skills to explore choice databases, build and estimate choice models using the Python package Biogeme, and perform statistical tests to compare different model specifications.

`Lab session 2` focusses on the Mixed Logit models. Students will gain proficiency in building and estimating various types of Mixed Logit models by altering assumptions about preference heterogeneity and distributions to capture unobserved taste heterogeneity. Furthermore, we will explore the impact of the number of draws on the estimation outcomes. 

`Lab session 3`  



## 3. Notes

* This repository provides all the materials from the lectures and hands-on labs to successfully complete the course.
* You can also work locally on your laptop if you want to. Here are instructions on how to do it.
* Make sure you use Python X or above
* The requirements.txt file contains all the Python dependencies needed to run the codes used in this course. In each notebook file, we provide two ways to set up your environments: (1) Google Colab and (2) Local. Note that this file may be updated during the course to include more dependencies.

## 4. Q&A Forum

In order to solve any doubt or facilitate communication, we will use the [Issues](https://github.com/SEN1221TUD/2023_internal/issues) section as the official forum of the course. In this section, you can post your questions, including questions related to the content of the lectures, specific questions about the lab sessions, and technical problems with Python. Before creating a new issue, please make sure the issue has not been raised before by one of your classmates. Besides asking questions, you can also comment on the earlier issues e.g. to continue the discussion. As an example, we have already created the first issue, see Issues and check it out.

To create a new issue (question or problem) in the course repository, follow these steps:

1. Go to the "Issues" section of the course repository.
2. Click on "New issue" in the green button located at the upper right corner of your screen.
3. Add an informative title to your question or problem (e.g., "logit model of BIOGEME does not import in my notebook").
4. Describe your issue clearly and concisely. 
5. Add a topic label from the right-hand side. Click on the gear icon next to "Labels" and choose the label based on the topic of your question. 
6. Click on "Submit new issue" in the green button below the text description.

After that, one instructor or teacher assistant will reply to your question. Also, you are allowed (even encouraged) to help others, if you can! If you know how to help your fellow student with an issue, share your thoughts and answers.

## 5. Instructions to set up your workspace

In this course, you will work with Python notebooks (Jupyter Notebooks) which can be easily opened in a local environment. It is recommended that you work locally on your laptop using the requirements file to install the necessary packages. However, you also have the option to use Google Colab.

### a. Local environment (recommended)

To get started, make sure you have a Python 3.11 or a newer version installed. Additionally, ensure you have set up an IPython environment on your computer(Jupyter, VSCode, or any alternatives). It's also beneficial to possess basic skills in working with virtual environments, especially if you prefer to keep your current dependencies separate.

Please follow the steps we've included below to set up the workspace.

* Step 1: Clone or download this repo to your computer (see Step 1 in the Colab section).
* Step 2: Two options: (a) Install dependencies separate from your current Python version; (b) Install dependencies for this notebook in your Python version (easy way):
    * Step 2. a (For those familiar with environments):
        * Create a new "virtual environment" (a separate workspace for your project).
        *  Install the required packages listed in the requirements_local.txt file within this environment.
        * Open the notebook you want to work on (Step 1) and make sure it's running in the newly created environment.
                         
    * Step 2. b (easy way):
        * Open the Python notebook you want to work on (Step 1)
        * Uncomment the line related to using a local set-up and run it (see the figure below).
        * Re-comment the lines to avoid re-installing the dependencies every time you run the notebook.
          ![image](https://github.com/SEN1221TUD/2023_internal/assets/130387534/f99e2410-912e-45c8-819e-69200630f853)

          
    * Creating a New Virtual Environment:

      To create one, you can follow these steps:
        * Open your command prompt or terminal.
        * Navigate to the directory where you want to create the environment.
        * Type: python -m venv myenv (Replace myenv with a name you choose for your environment).
        * Activate the environment (on Windows, type: myenv\Scripts\activate, on MacOS/Linux, type: source myenv/bin/activate).
          
    * Installing Requirements from a File:
        * With your environment activated, navigate to the folder containing the requirements_local.txt file and run: pip install -r requirements_local.txt.


### b. Google Colab 

The minimum requirements to get started are quite simple. You will need a Google account, the Google Chrome web browser and a stable internet connection. These essentials will allow you to work smoothly as you immerse yourself in the course material.

Please follow the steps we've included below to set up the workspace.

* Step 1: Download this repo to your computer. On the top of this site, click on (1)<>Code tab, then in the green button (2)Code and then (3) Download ZIP (See numbers 1, 2, and 3 on the following image). Unzip this file into a working folder of your own choice.

  ![image](https://github.com/SEN1221TUD/2023_internal/assets/130387534/eb315f01-9476-45ca-8a56-60f421695bb3)


* Step 2: Go to http://colab.research.google.com

* Step 3: Sign in with your Google account (if you are already signed in, skip this step). If you do not have a Google account, you must (temporarily) create one.

* Step 4: Upload the Python notebook you want to work on to Colab. Click on the "Upload" tab and then on the "Choose file" tab, see numbers 1 and 2 in the figure below. Then, navigate to your working folder (Step 1) and select the Python notebook (.ipynb) you want to work on (e.g. lab_session_00.ipynb).
  ![image](https://github.com/SEN1221TUD/2023_internal/assets/130387534/ec1ee58e-7d68-46e5-85e4-542c24d8b29e)
  
* Step 5: Once open, click on "View" >> "Expand sections" on the menu bar.

* Step 6: Importantly, Each notebook has a cell to prepare the data and environment in Google Colab. Uncomment (i.e. remove the '#') the lines related to the Colab set-up in your notebook, see the figure below. Run this cell and wait until finished.


![image](https://github.com/SEN1221TUD/2023_internal/assets/130387534/8e65c497-417a-4c35-9893-93a0ea4a88e0)


* Step 7: You are all set! You can work on your notebook.


   



