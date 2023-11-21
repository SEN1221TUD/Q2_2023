# SEN1221- Statistical Analysis of Choice Behaviour

## 1. Introduction

Welcome to the git repository of Statistical Analysis of Choice Behaviour (part 1). Here, you find notebooks for the lab sessions. Please review the following information carefully.

## 2. Description

Discrete Choice Models (DCMs) are widely used to study the decision-making behaviour of individuals across numerous scientific domains, including transportation, marketing, and health, among others. DCMs are particularly used to infer tastes and preferences over attributes and alternatives, forecast demand, and predict the impact of new policies.

This course aims to equip students in the socio-technical domain with a comprehensive understanding of DCMs. It prepares students to develop diverse models to generate solutions to societal  challenges. 

The course consists of oral lectures and lab sessions. While attendance at lectures and lab sessions is highly recommended to keep up with the course, it is not mandatory.

## Lab sessions
Lab sessions aim to demonstrate and reinforce knowledge about different discrete choice models, the underlying assumptions, estimation techniques, and how to interpret model outcomes. They provide hands-on experience in discrete choice modelling. The lab sessions include a series of exercises in the form of Jupyter notebooks. 

`Lab session 1` introduces discrete choice models, focusing specifically on the Multinomial Logit (MNL) model based on random utility theory. You will acquire skills to explore choice datasets, build and estimate choice models using specialised Python package called Biogeme, and perform statistical tests to compare different model specifications.

`Lab session 2` focusses on the Mixed Logit models. Students will gain proficiency in building and estimating various types of Mixed Logit models by altering assumptions about unobserved preference and taste heterogeneity. Furthermore, you will explore the impact of the number of draws on the estimation outcomes. 

`Lab session 3` focusses on the latest developments in the field: combining discrete choice modelling and machine learning for choice behaviour analysis. You will work with neural networks and explore how they can be integrated within utility-based choice models.   

For the lab sessions, we use Python notebooks (Jupyter Notebooks). You have two options to work in them:
A. Local environment (recommended)
B. Google Colab

For both options, **instructions** to set up your Python environment are given at the **end of this page**.
Accordingly, in each notebook file, we provide two ways to set up your environments: 
(1) Local
(2) Google Colab 

If you are **unfamiliar with Python**, we recommend completing **lab session 0**, which provides the necessary tools to conduct the lab sessions. It covers topics such as data structures, utilising external libraries, data exploration, visualisation, etc. 

## 4. Q&A Forum

We use the [Issues](https://github.com/SEN1221TUD/Q2_2023/issues) section as the Q&A platform of this course (part 1). Here, you can post your questions related to the content of the lectures,  the lab sessions, and technical problems with Python. Before you create a new issue, please make sure the issue has not been raised before by one of your classmates. Besides asking questions, you can comment on the earlier issues e.g. to continue the discussion. As an example, we have already created the first issue; see [Issues](https://github.com/SEN1221TUD/Q2_2023/issues).

To create a new issue (question or problem) in the course repository, follow these steps:

1. Go to the "Issues" section of the course repository.
2. Click on "New issue" in the green button located at the upper right corner of your screen.
3. Add an informative title to your question or problem (e.g., "logit model of BIOGEME does not import in my notebook").
4. Describe your issue clearly and concisely. 
5. Add a topic label from the right-hand side. Click on the gear icon next to "Labels" and choose the label based on the topic of your question. 
6. Click on "Submit new issue" in the green button below the text description.

After that, the lecturer or teaching assistant will reply to your question. Also, you are allowed (even encouraged) to reply to questions posted by your fellow students! If you know how to help your fellow student with an issue, share your thoughts!

## 5. Instructions to set up your workspace

### a. Local environment (recommended)

To get started, make sure you have Python 3.7 or a more recent version up to 3.10 installed. Additionally, ensure you have set up an IPython environment on your computer (Jupyter, VSCode, or any alternatives). 

Please follow the steps below to set up your environment.

* Step 1: Clone or download this repo to your computer (see Step 1 in the Colab section).
* Step 2: Now you have two options: (a) Install dependencies separate from your current Python version; (b) Install dependencies for this notebook in your Python version (easy way):
    * Option a: (for those familiar with Python environments):
        * Create a new "virtual environment" (a separate workspace for this course).
        * Install the required packages listed in the requirements.txt file within this environment.
        * Open the notebook you want to work on (Step 1) and make sure it's running in the newly created environment.
                         
    * Option b: (easiest way; for people unfamiliar with Python environments):
        * Open the Python notebook you want to work on (Step 1)
        * Uncomment the line related to using a local set-up and run it (see the figure below).
        * Re-comment the lines to avoid re-installing the dependencies every time you run the notebook.
          ![image](https://github.com/SEN1221TUD/Q2_2023/blob/main/Assets/img_1.png)



    * Instructions for creating a new virtual environment (if choose option a):
        * Open your command prompt or terminal.
        * Navigate to the directory where you want to create the environment.
        * Type: python -m venv myenv (Replace myenv with a name you choose for your environment).
        * Activate the environment (on Windows, type: myenv\Scripts\activate, on MacOS/Linux, type: source myenv/bin/activate).
        * Install requirements from a File. With your environment activated, navigate to the folder containing the requirements.txt file and run: pip install -r requirements.txt.


### b. Google Colab 

For this option, you need a Google account,  the Google Chrome web browser, and a stable internet connection.

Please follow the steps we've included below to set up the workspace.

* Step 1: Download this repo to your computer. On the top of this site, click on (1)<>Code tab, then in the green button (2)Code and then (3) Download ZIP (See numbers 1, 2, and 3 on the following image). Unzip this file into a working folder of your own choice.

   ![image](https://github.com/SEN1221TUD/Q2_2023/blob/main/Assets/img_2.png)


* Step 2: Go to http://colab.research.google.com

* Step 3: Sign in with your Google account (if you are already signed in, skip this step). If you do not have a Google account, you must (temporarily) create one.

* Step 4: Upload the Python notebook you want to work on to Colab. Click on the "Upload" tab and then on the "Choose file" tab, see numbers 1 and 2 in the figure below. Then, navigate to your working folder (Step 1) and select the Python notebook (.ipynb) you want to work on (e.g. lab_session_00.ipynb).
  ![image](https://github.com/SEN1221TUD/Q2_2023/blob/main/Assets/img_3.png)
  
* Step 5: Once open, click on "View" >> "Expand sections" on the menu bar.

* Step 6: Importantly, Each notebook has a cell to prepare the data and environment in Google Colab. Uncomment (i.e. remove the '#') the lines related to the Colab set-up in your notebook, see the figure below. Run this cell and wait until finished.


 ![image](https://github.com/SEN1221TUD/Q2_2023/blob/main/Assets/img_4.png)




* Step 7: The necessary packages will be loaded, don't worry about the warning messages that will appear, you're all set! You can now work on your laptop.

Finally, note that the requirements files may be updated during the course to include more dependencies if needed.
   

### c. Anaconda

If you want to use Anaconda, you must use **Python version 3.9.18 or 3.10.13**. Other versions, such as **3.7.16** and **3.8.18**, are known to give problems. Python version **3.11.5** seems to be working, but is not very stable.

##### Instruction 1: Create environment and install requirements from JupyterLab.

1. **Open the environments Tab:** Go to the "Environments" tab on the left sidebar.
   ![img1](https://github.com/SEN1221TUD/Q2_2023/blob/main/Assets/Anaconda_1.png)

2. **Create a new environment:** Click on the "Create" button at the bottom of the window.

    ![img2](https://github.com/SEN1221TUD/Q2_2023/blob/main/Assets/Anaconda_2.png)
   
3. **Configure the new environment:** Enter a name for your new environment, e.g., "SEN1221," and choose the Python version == “**3.10.13**" from the drop-down menu.

    ![img3](https://github.com/SEN1221TUD/Q2_2023/blob/main/Assets/Anaconda_3.png)
   
4. **Activate the environment:** Go back to the "Home" tab. You should see your newly created environment at the right-hand side of "All applications"
 
   ![img4](https://github.com/SEN1221TUD/Q2_2023/blob/main/Assets/Anaconda_4.png)
   
5. **Install and launch JupyterLab.**
 
   ![img5](https://github.com/SEN1221TUD/Q2_2023/blob/main/Assets/Anaconda_5.png)
   
6. **Set up the working folder:** Download the SEN1221/Q2_2023 repo from the github repo to your computer . Unzip the file into a working folder of your own choice.

7. **Find workspace through JupyterLab:** You will see the Lab session, the `requirements.txt` file, and the `data` folder.
 
   ![img6](https://github.com/SEN1221TUD/Q2_2023/blob/main/Assets/Anaconda_6.png)
   
8. **Uncomment and run the following cell:**

   ![img7](https://github.com/SEN1221TUD/Q2_2023/blob/main/Assets/Anaconda_7.png)
   
9. **Import all packages**
 
   ![img8](https://github.com/SEN1221TUD/Q2_2023/blob/main/Assets/Anaconda_8.png)
   
In case a package has not been imported, please restart the kernel and repeat steps: 8 and 9
 
   ![img9](https://github.com/SEN1221TUD/Q2_2023/blob/main/Assets/Anaconda_9.png)
   
#### Instruction 2: Create environment and install the requirements through the terminal.

1. **Open the environments tab:** Go to the "Environments" tab on the left sidebar.

   ![img10](https://github.com/SEN1221TUD/Q2_2023/blob/main/Assets/Anaconda_10.png)

2. **Create a new environment:** Click on the "Create" button at the bottom of the window.

   ![img11](https://github.com/SEN1221TUD/Q2_2023/blob/main/Assets/Anaconda_11.png)

3. **Configure the new environment:** Enter a name for your new environment, e.g., "SEN1221," and choose the Python version == “3.10.13" from the drop-down menu.

   ![img12](https://github.com/SEN1221TUD/Q2_2023/blob/main/Assets/Anaconda_12.png)

4. **Activate the environment:** Click on the green "Play" button on the right side of the environment name to open a terminal where the environment is activated.

   ![img13](https://github.com/SEN1221TUD/Q2_2023/blob/main/Assets/Anaconda_13.png)

5. **Verify Python version:** You can run `python --version` in the terminal.

   ![img14](https://github.com/SEN1221TUD/Q2_2023/blob/main/Assets/Anaconda_14.png)

6. **Navigate to the project folder:** Use the `cd` command to navigate to the project folder, for example, `cd …/…/…/Q2_2023`.

   ![img15](https://github.com/SEN1221TUD/Q2_2023/blob/main/Assets/Anaconda_15.png)

7. **Install requirements file:** Now, you can install the `requirements.txt` file within the activated environment using the following command: `pip install -r requirements.txt`

   ![img16](https://github.com/SEN1221TUD/Q2_2023/blob/main/Assets/Anaconda_16.png)
  
8. **Install and launch JupyterLab**

   ![img17](https://github.com/SEN1221TUD/Q2_2023/blob/main/Assets/Anaconda_17.png)
   
9. **Import all packages**

   ![img18](https://github.com/SEN1221TUD/Q2_2023/blob/main/Assets/Anaconda_18.png)