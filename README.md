# Automating the Examination System

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/d09135d8cce145e797fd14636bd94d95)](https://app.codacy.com/manual/nityansuman/automated-test-app?utm_source=github.com&utm_medium=referral&utm_content=nityansuman/automated-test-app&utm_campaign=Badge_Grade_Dashboard)


Conducting examination and answer sheet evaluation are hectic testing tools for assessing
academic achievement, integration of ideas and ability to recall, but are expensive, resource
and time consuming to generate question and evaluate response manually. Manual evaluating
of answer sheet takes up a significant amount of instructors' valuable time and hence is an
expensive process. Also different security concerns regarding paper leakage is one of the other
challenges to conquer. This project aims to build an automated examination system using
machine learning, natural language toolkit (NLTK), python environment, flask framework,
and web technologies to provide an inexpensive alternative to the current examination system.
We implement a model to automatically generate questions with their respective answers and
assess user responses.

![Image](images/home.png)

## Install Prerequisites and Run

```
# Download/clone the project from github
$ git clone https://github.com/nityansuman/automated-test-app/.git

# Create a project environment with Anaconda
$ conda create --name envname python
$ conda activate envname

# Install and set-up required packages
$ pip install -r REQUIREMENTS.txt

# Download NLTK corpus (If not present already)
>>> import nltk
>>> nltk.download("all")
>>> exit()

# Navigate to the root folder
$ cd automated-test-app/

# Run
$ python runserver.py
```

## Important Links

* [How to install anaconda python distribution ?](https://docs.anaconda.com/anaconda/install/)
* [Natural Language Processing](https://nltk.org/book/)
* [Git](https://git-scm.com/)
* [Github](https://github.com/)
* [NLTK](https://nltk.org/)
* [Flask](http://flask.pocoo.org/)
* [Web Development](https://w3schoo.com/)
* [Python](https://python.org/)
* [Anaconda Python Distribution](https://conda.io)

Drop me a mail or connect with me on [Linkedin](https://linkedin.com/in/kumar-nityan-suman/) .

If you like the work I do, show your appreciation by 'FORK', 'STAR' and 'SHARE'.