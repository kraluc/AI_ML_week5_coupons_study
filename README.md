# Will the customer accept the coupon?

## Overview

In this first practical application assignment of the program, you will seek to answer the question, “Will a customer accept the coupon?” The goal of this project is to use what you know about visualizations and probability distributions to distinguish between customers who accepted a driving coupon versus those that did not. Use the [Coupon Jupyter Notebook](./Coupon.ipynb) to complete this assignment.

## Data

This [data](https://archive.ics.uci.edu/ml/machine-learning-databases/00603/in-vehicle-coupon-recommendation.csv) comes to us from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios, including the destination, current time, weather, passenger, etc., and then asks people whether they will accept the coupon if they are the driver. Answers given that the users will drive there “right away” or “later before the coupon expires” are labeled as “Y = 1”, and answers “no, I do not want the coupon” are labeled as “Y = 0”. There are five different types of coupons—less expensive restaurants (under $20), coffee houses, carry out and take away, bars, and more expensive restaurants ($20–$50).

## Deliverables

Your final product should be a brief report that highlights the differences between customers who did and did not accept the coupons. To explore the data, you will utilize your knowledge of plotting, statistical summaries, and visualization using Python. You will publish your findings in a public facing GitHub repository as your first portfolio piece.

This is a required assignment and counts toward program completion.

## Submission Instructions

Submit the website URL to your public-facing GitHub repository here
Your learning facilitators will grade your submission according to the rubric below.

### Getting started (macOS)

Use the virtual environment of your choice and install the recommended python modules.

### prerequisites

1. Install [homebrew](https://brew.sh/)

2. Install [Git](https://github.com/git-guides/install-git)

3. Install [pipenv](https://pipenv.pypa.io/en/latest/installation/)

```python
pip install --upgrade pipenv
```

#### pipenv example

1. Create virtual environment with Python version (must already be installed)

```python
pipenv --python 3.10
```

2. Install modules

* When a requirements.txt file is present, pipenv will automatically install those when you first run ```pipenv install```

* Requirements were generated as follows

```
pipenv install seaborn matplotlib numpy pandas
```

```python
Installing plotly...
Adding plotly to Pipfile's [packages]...
✔ Installation Succeeded
Installing seaborn...
Adding seaborn to Pipfile's [packages]...
✔ Installation Succeeded
Installing matplotlib...
Adding matplotlib to Pipfile's [packages]...
✔ Installation Succeeded
Installing numpy...
Adding numpy to Pipfile's [packages]...
✔ Installation Succeeded
Installing pandas...
Adding pandas to Pipfile's [packages]...
✔ Installation Succeeded
Pipfile.lock not found, creating...
Locking [dev-packages] dependencies...
Locking [packages] dependencies...
Building requirements...
Resolving dependencies...
✔ Success!
Updated Pipfile.lock (033c10)!
Installing dependencies from Pipfile.lock (033c10)...
  🐍   ▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉ 0/0 — 00:00:00
To activate this project's virtualenv, run pipenv shell.
Alternatively, run a command inside the virtualenv with pipenv run.
```

```python
pipenv run pip freeze > requirements.txt
```

## Practical Application Assignment 5.1

### Criteria 1 - Project Organization

* A README file with summary of findings and link to notebook
* Jupyter notebook with headings and text appropriately formatted
* No unnecessary files
* Directories and files have appropriate names and location
