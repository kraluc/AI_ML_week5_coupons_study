# Will the customer accept the coupon?

## Overview

In this first practical application assignment of the program, you will seek to answer the question, “Will a customer accept the coupon?” The goal of this project is to use what you know about visualizations and probability distributions to distinguish between customers who accepted a driving coupon versus those that did not.
<br></br>

## Methodology

Analysis based on Data set: in-vehicle coupon recommendation

+ [Data folder](https://archive.ics.uci.edu/ml/machine-learning-databases/00603/)
+ [Attribute information](https://archive.ics.uci.edu/ml/datasets/in-vehicle%20coupon%20recommendation#)
+ [Coupon Jupyter Notebook](./Coupon.ipynb)
  (prerequisites: ```pip install -r [requirements.txt](requirements.txt)```

## Findings

1. Preferred coupon categories: **"Carry out & Takeaway"** and **"Restaurants (<20)"**
    ![User Coupon Preferences](images/user_preferences.jpg "User preferences")

2. **Differences between customers who did and did not accept the coupons.**
    ![User education](images/user_education.jpg "User education")

## Grading Criteria

### Criteria 1 - Project Organization (20 pts)

+ [x] A README file with summary of findings and link to notebook
+ [x] Jupyter notebook with headings and text appropriately formatted
+ [x] No unnecessary files (used .gitignore)
  + included [requirements.txt](requirements.txt) file for easier setup
  + may include downloaded copy of .csv
+ [x] Directories and files have appropriate names and location

### Criteria 2 - Syntax and Code quality (20 pts)

+ [X] Libraries are imported and aliased correctly
+ [ ] Code does not contain errors
+ [ ] No long strings of code output
+ [ ] Demonstrates competency with pandas
+ [ ] Demonstrates competency with seaborn
+ [ ] Comments are used appropriately to explain code
+ [ ] Variables are sensible

### Criteria 3 - Visualizations (30 pts)

+ [ ] Appropriate plots for categorical and continuous variables are utilized
+ [X] Plots contain human readable labels
+ [X] Plots contain descriptive titles
+ [X] Axes are legible
+ [ ] Subplots are used when appropriate
+ [ ] Plots are scaled appropriately for readability

### Criteria 4 - Findings (30 pts)

+ [ ] Clearly stated problem for specific coupon group
+ [ ] Visualizations that demonstrate exploring differences in those who accepted and rejected the coupon
+ [ ] Interpretation of descriptive and inferential statistics is correct and concise
+ [ ] The findings are clearly stated in their own section with actionable items highlighted
+ [ ] Next steps and recommendations
