# Comment Sentiment Analysis
Categorize whether a comment on a product is positive or negative.
Use supervised machine learning model to classify the sentiment of a comment.
Use Python with the support of scikit-learn, numpy, and pandas.
The data for this project is in Vietnamese, but the code can be reused for other languages as well.

## Prerequisites
Make sure you have installed all of the following prerequisites on your computer:
- Python 3.0 or later.
You can download different versions of Python here:
http://www.python.org/getit/
- `pip`

## Installation

#### 1. Install and activate virtual environment
Make sure that you already are in root directory of the project before running the following code.
```
$ pip install virtualenv
$ virtualenv venv --python=python3.8
$ source venv/bin/activate
```

#### 2. Install requirements
To install all the required libraries and packages for this project, run this command in your terminal:
```
pip install -r requirements.txt
```

## Run the program
Run the program's phases in order of data preprocessing, model training, and result evaluation by running these following commands in your terminal, one after another:
- Data Preprocessing
```
$ python preprocess.py
```
- Model Training
```
$ python train.py
```
- Result Evaluation
```
$ python evaluate.py
```
A detailed report about the model's accuracy will be returned in your terminal.
