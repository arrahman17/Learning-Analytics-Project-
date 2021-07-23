# Learning Analytics Based Student Enrollment and Performance Analysis(SEPA)

# Project Overview

 **Introduction**
  
  This project is aim to analyse student performance and enrolment.  We have collected raw data from students based on their previous grades. The project has two parts, one is system will classify Grades into two catageories Good or Bad using Sciket learn with the help of Machine learning techniques, and in second part we visualize the pre-processed data using D3.js.
  
# Features
**Analysis of Student Data**
 - Subject wise performance 
 - Sub-continent wise enrolment analysis
 - Department wise analysis 
 - Analysis of source of Study
 - Prediction of Good or Bad Grades ( In Mainly Machine Learning part)

  
# Project Architecture

![github-small](https://user-images.githubusercontent.com/41241181/52539005-b73c8400-2d79-11e9-9cc5-68bb8a4e4bb6.png)

# Libraries/Algorithms

**Algorithm for Analysis**

- Logistic Regression
- KNeighbours Classifier
- Random Forest Classifier 
- SVC(Support Vector Classifier)

**Libraries and Tools for Analysis**

- Sciket learn using Python
- Libraries: Pandas, numpy
	
	
 ![github-small](https://user-images.githubusercontent.com/41241181/52512081-5f7c0c80-2c03-11e9-9450-a6833f67adeb.png)
 
 ![github-small](https://user-images.githubusercontent.com/41241181/52512106-7ae71780-2c03-11e9-975f-62202d529dc6.png)

**Tools for Visualization**

 - D3.js 
 - Node.js
 
 ![github-small](https://user-images.githubusercontent.com/41241181/52514899-226d4580-2c16-11e9-9c0b-e3d91c7533bd.png)

 ![github-small](https://user-images.githubusercontent.com/41241181/52515067-8e9c7900-2c17-11e9-90da-38ad8468c185.png)

# Screenshots of the Visualization

**Simple Bar Charts**

- Department wise Enrollment Analysis 
![github-small](https://user-images.githubusercontent.com/41241181/52512797-2ba2e600-2c07-11e9-9f09-e5493fbc425b.png)

- Country wise Enrollment analysis 
![github-small](https://user-images.githubusercontent.com/41241181/52512800-2d6ca980-2c07-11e9-8cd7-41f329965eef.png)

- Sub-Continent wise Enrollment Analysis 
![github-small](https://user-images.githubusercontent.com/41241181/52512802-2f366d00-2c07-11e9-8396-fadd5878a26a.png)

- Learning Resource 
![github-small](https://user-images.githubusercontent.com/41241181/52512804-30679a00-2c07-11e9-919b-fa1f0ed80b46.png)

**Interactive Bar Charts**

- Department wise Student Enrollment Analysis for year 2019
![github-small](https://user-images.githubusercontent.com/41241181/52513091-c819b800-2c08-11e9-88ce-99881fe4cdaf.png)

- German Student Analysis 
![github-small](https://user-images.githubusercontent.com/41241181/52513094-cb14a880-2c08-11e9-9a3e-0d6767f5018c.png)

- Internationl Students Analysis
![github-small](https://user-images.githubusercontent.com/41241181/52513095-ccde6c00-2c08-11e9-9bdf-33bb0f8d7082.png)

- Grade Average for each Department 
![github-small](https://user-images.githubusercontent.com/41241181/52513097-ce0f9900-2c08-11e9-8615-4d75981dd8ac.png)

## Installation

**Installation for Machine learning**

Install python with jupyter Notebook and as well as the libraries Pandas and Numpy 

If you are Mac or Linux user, you can use the commands, otherwise follow the links for each installations

- [Python 2.7](https://www.python.org/downloads/)   - Download it 

- [Pip](https://pip.pypa.io/en/stable/installing/)   -  On linux or mac "pip install -U pip" for windows "python -m pip install -U pip"

- [NumPy 1.6.1](http://sourceforge.net/projects/numpy/files/NumPy/1.10.2/)   - pip install numpy

- [SciPy 0.9](http://sourceforge.net/projects/scipy/files/scipy/0.16.1/)   -pip install scipy

- [Pandas](https://pandas.pydata.org/pandas-docs/stable/install.html)   - pip install pandas

- [scikit-learn](http://scikit-learn.org/stable/install.html)   -pip install sciket-learn

Installing Jupyter using Pip

Open command Terminal and write down these commands 

- python -m pip install --upgrade pip
- python -m pip install jupyter

Here are the links 

 - [How to Install Jupyter Notebook](https://jupyter.org/install) 
 
 - [How to Install Sciket Learn](https://calebshortt.com/2016/01/15/installing-scikit-learn-python-data-mining-library/)

After Installing it, Open Terminal and type "Jupyter Notebook " if its works Congratulations you have installed sucessfully


**How to Run**

   - Clone our project folder , specially the "LA_project_grades_analysis.ipynb" file and "final_data.tsv"

   - Open Terminal and write Jupyter Notebook, and then open the "LA_project_grades_analysis.ipynb" 
   
   - Set your path for Dateset with name "final_data.tsv"

   - Run it line by line 
   

**Installation for Visualization**

   First make sure you have node installed , if you do not have installed then go to official [Node](https://nodejs.org/en/) web page  and download the latest version. 

![github-small](https://user-images.githubusercontent.com/41241181/52513674-acb0ac00-2c0c-11e9-9b87-3f36287926ba.png)
 
 write these command to check Node and NPM is properly installed 

- For Node.js "node --version "
- For NPM  "npm --version "

After Installing Node, download the [D3.Js librray](https://d3js.org/)  , if you want to start with a new project 

![github-small](https://user-images.githubusercontent.com/41241181/52513614-4035ad00-2c0c-11e9-8a32-fc4499a5d3d6.png)



**How to Run**


Clone our project and open the one of the visualization folder 

To Run it locally, open the terminal in folder where the visualization code reside, here in the case we have in "Visualization using simple bar charts " 

- write the follwoing commands 

  - npm install -g http-server
  - http-server 
  
- Server address
  -  http://localhost:8080
  
Same as for Interactive bar chart folder 

**[Demo](https://www.youtube.com/watch?v=vnm1HM-NzBY&feature=youtu.be)**

# Group Members

- Abdul-Rahman, khan 
- A.B.M. Rocknuzzaman 
- Piush, Aggarwal
- Amin, Shahin 
- Tianyu, Zhu
- Muhammad, Zeeshan 
- Ghulam Dawood Nasimi

# Evaluation 
**Special Thanks to [SOCO TEAM](https://www.uni-due.de/soco/people.php)**
  
  - This project was not possible without the help and motivition of [Prof. Dr. Mohamed Amine Chatti](https://www.uni-due.de/soco/people/mohamed-chatti.php) and [Dr. Arham Muslim](https://www.uni-due.de/soco/people/arham-muslim.php)

 **We are very thankful to [Prof. Dr. Mohamed Amine Chatti](https://www.uni-due.de/soco/people/mohamed-chatti.php) and [Dr.    Arham Muslim](https://www.uni-due.de/soco/people/arham-muslim.php)**

 - For providing us such a platform to learn the theoritical concept as well as the practical skills
 - To improve communication, presentation ,theoritical and practical skills 
 - And having the oppurtunity to Brainstorm ideas during workshops and as well as have the chance to work with globally minded  students 
 - This project was the part of Learning Analytics course in UDE
 

# Version 
1.0




