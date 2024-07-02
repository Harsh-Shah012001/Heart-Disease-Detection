# Heart-Disease-Detection
Data: https://b2gdevs.github.io/MLIntro/heart-disease.html

# Support Vector Machines
SVM offers very high accuracy compared to other classifiers such as logistic regression, and decision trees. It is known for its kernel trick to handle nonlinear input spaces. It is used in a variety of applications such as face detection, spam classification, classification of genes etc.

The SVM classifier (SVC) separates data points using a hyperplane with the largest amount of margin. That's why an SVM classifier is also known as a discriminative classifier. SVM finds an optimal hyperplane which helps in classifying new data points.

# Web-Scraping 
Selenium is an open-source web-based automation tool. Selenium primarily used for testing in the industry but It can also be used for importing webdriver & web scraping.

# Dataset Description
We will be Scraping 13 input Features along with the target. The objective is predict the presence of heart disease in the patient.

Data Dictionary :

age<br/>
sex
cp : chest pain type (4 values)
trestbps : resting blood pressure
chol : serum cholestoral in mg/dl
fbs : fasting blood sugar > 120 mg/dl
restecg : resting electrocardiographic results
thalach : maximum heart rate achieved
exang : exercise induced angina
oldpeak : ST depression induced by exercise relative to rest
slope : the slope of the peak exercise ST segment
ca : number of major vessels (0-3) colored by flourosopy
thal : integers representing normal, fixed defect, reversable defect

# Result Analysis
The dataset has a linear trend. As the performance of SVM Classifier with linear and rbf kernel is better than polynomial kernels. But, in case of rbf kernel the log-loss score is least. so, it can be said that for the given dataset rbf kernel works best.
