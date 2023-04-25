## Project: Covid-19-Mortality-Prediction

### Install

The following Python libraries are installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://jupyter.org/install.html) or [Google Colab](https://colab.research.google.com/)

### Code

Code is present in `Covid_19_Mortality_prediction.ipynb` notebook file. The dataset used in the notebook is present in **data** folder and is named *Covid Data.csv*

### Data

The Covid 19 dataset consists of 21 unique features and 1,048,576 unique patients samples in the dataset. 
This dataset is found on [Kaggle](https://www.kaggle.com/datasets/meirnizri/covid19-dataset).

**Features**

- patient type: type of care the patient received in the unit. 1 for returned home and 2 for hospitalization.
- pneumonia: whether the patient already have air sacs inflammation or not.
- pregnancy: whether the patient is pregnant or not.
- diabetes: whether the patient has diabetes or not.
- copd: Indicates whether the patient has Chronic obstructive pulmonary disease or not.
- asthma: whether the patient has asthma or not.
- inmsupr: whether the patient is immunosuppressed or not.
- hypertension: whether the patient has hypertension or not.
- cardiovascular: whether the patient has heart or blood vessels related disease.
- renal chronic: whether the patient has chronic renal disease or not.
- other disease: whether the patient has other disease or not.
- obesity: whether the patient is obese or not.
- tobacco: whether the patient is a tobacco user.
- usmr: Indicates whether the patient treated medical units of the first, second or third level.
- medical unit: type of institution of the National Health System that provided the care.
- intubed: whether the patient was connected to the ventilator.
- icu: Indicates whether the patient had been admitted to an Intensive Care Unit.

**Target Variable**

- death: If the patient would die given the features for the respective patient, 1 indicates death and 0 otherwise

### Models

1. Standard Classification Models

- Logistic Regression
- XG Boost
- Decision Trees

2. Custom Models

- Classifier-Classifier Ensemble
- Supervised-Unsupervised Ensemble

### Authors

1. Rahul Chauhan
2. Irlanki Sandeep
3. Rohan Sarnad
4. Anirudh S Bhargav

