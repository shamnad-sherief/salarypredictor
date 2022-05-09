
# SalaryPredictor

SalaryPredictor can predict your salaries according to your years of experience in a job

# Introduction

This is a Data Science project based on Simple Linear Regression Algorithm. Simple linear regression models a variable Y as being, aside from a random error, a linear function of another variable X. The parameters of this linear relationship are unknown and need to be estimated.


The accuracy of a Simple Linear Regression depends on the trained set and the tested set. Graph which represents the accuracy of the algorithm is given below:-

![Screenshot from 2022-04-29 16-05-11](https://user-images.githubusercontent.com/66134967/165928960-80eeefd6-e477-459b-ad40-d0388e7b79b2.png)



![image](https://user-images.githubusercontent.com/66134967/165929078-77a93c46-7f68-4ca1-8682-bac547cba2ab.png)







## Usage

Simply put your year of experience in the box and click the submit button


## Installation

Clone the repo:

```bash
git clone https://github.com/shamnad-sherief/salarypredictor.git
```
Navigate to the project folder   
```bash
cd salarypredictor
```
Create a Virtual Environment (Optional)
```bash
 python -m venv env
```
Activate the virtual environment

   **Linux**
   ```bash
    source env/bin/activate 
   ```
   **Windows**
   ```bash
    env\Scripts\activate 
   ```
Install dependencies
```bash
 pip install -r requirements.txt 
```
Running with flask

**Linux**
```bash
 export FLASK_APP=form
 flask run
```
**Windows**
```bash
 set FLASK_APP=form
 flask run
```

 Go to ```  http://127.0.0.1:5000 ``` in your browser  after successfull completion
 
 ## Deployment
 
 Clone the repo:

```bash
git clone https://github.com/shamnad-sherief/salarypredictor.git
```
 Install Heroku-CLI and login
 ```bash
heroku login
```
Navigate to the project folder   
```bash
cd salarypredictor
```
Git should be initialized in the working directory:
```bash
git init
```
Create you app-name (salarypredictor)
```bash
heroku create salarypredictor
```
Adding Heroku remote 
```bash
heroku git:remote -a salarypredictor
```
Install dependencies
```bash
 pip install -r requirements.txt 
```
Make sure gunicorn is installed with requirements

Commiting changes
```bash
git add .
git commit -m 'your message'
git push heroku main
```
Checking the status of your deployement
```bash
heroku ps:scale web=1
```
To open your website
```bash
Heroku open
```
Follow the link and chao



