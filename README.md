# Bankruptcy Prediction Using Machine Learning


## Machine Learning approach:
-	To make good use of our dataset we decided to train 3 different machine learning models such that each model depends on different algorithms than the others.
-	Before being able to train the models, dataset had to be prepared first by removing duplicates, null or missing values, outliers 
-	All models were trained using a part of the data set and tested using the other part
<br>	
--	The first model was trained using Logistic Regression, it had  accuracy of  68%
<br>	

--	Second model was trained using Decision tree, and it was a great leap forward as the accuracy has improved to about 80% to 85%, depending on the random portion of dataset used during the training.
<br>	
--	Third model was trained using Support Vector Machine (svm) and had accuracy of 72%
<br>	
-	“scikit-learn” library from “Conda” environment with python 3.9 was used to train the models and “joblib” to save them as binaries for later use
-	 A Jupyter notebook was used to divide code into cells to be easy for reading and documenting along the whole study 
-	To test for an observation, the required attributes need to be passed in form of (.CSV) file to the model
-	Each model produces output of:
either (1: “Bankruptcy”) or (0: “Doesn’t have Bankruptcy”)
 
## Introduction:
	
Bankruptcy prediction is an important problem in finance since successful predictions would allow stakeholders to 
take early actions to limit their economic losses. Recently, AI models have increasingly been used in bankruptcy 
prediction. For any bank or financial institution, Bankruptcy prediction is of utmost importance. The aim is, therefore, to 
predict bankruptcy of financial institutions using machine learning classifiers
<br>


I decided to analyze this subject statistically using graphical and numerical methods and train a machine learning model that can make good use of the dataset.
<br>
## Summary of research:

### Dataset source: 
fedesoriano. (September 2021). Heart Failure Prediction Dataset. Retrieved [December 2021] from https://www.kaggle.com/fedesoriano/heart-failure-prediction.
<br>

### Dataset details:
the dataset comes in form of a ‘‘.CSV’’ file, it will be analyzed using “Pandas” and “Matplotlib” libraries on python 3.9 using “Jupyter Notebooks” with “Conda” environment and it contains 12 attributes divided into columns which are: <br>

it contains 66 columns ( ID , Attr(1 - 64) , Class)

<br>
