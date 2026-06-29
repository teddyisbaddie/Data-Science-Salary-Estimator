# Data-Science-Salary-Estimator
The Data Science Salary Estimator is a machine learning application that predicts the salary of a data science job based on information from a job posting, such as required skills, company details, job title, and location.

Instead of manually comparing hundreds of job listings, a user can enter the characteristics of a job, and the model estimates the expected salary.

Features
•Predicts estimated salary based on user inputs
•User-friendly interface
•Machine learning regression model
•Data preprocessing and feature engineering
•Model evaluation using performance metrics
•Easy to deploy

Technologies Used
Python
Pandas
NumPy
Scikit-learn
Matplotlib
Flask (or Streamlit)
HTML/CSS (if using Flask)

Web Scraping
Tweaked the web scraper github repo (above) to scrape 1000 job postings from glassdoor.com. With each job, we got the following:

Job title
Salary Estimate
Job Description
Rating
Company
Location
Company Headquarters
Company Size
Company Founded Date
Type of Ownership
Industry
Sector
Revenue
Competitors

