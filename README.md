# Customer Conversion Prediction

### Kuldip Bhimani
### kuldipbhimani@gmail.com
### Batch : DS41


## Project Description :
In this project. We're going to predict if the customer will subscribe to our term insurance or not in telephonic marketing campaign using Machine Learning Models. So company's marketing campaign can become Cost and Time effective. We can first praioritly target potential clients with more effective way.

# 

## Project Approach & Tech - Stack Used :
In this project, I've used different Machine Learning Classification Models on our historical data to do prediction and get different level of accuracy and AUROC scores for evaluation.

I used Jupyter Notebook as IDE for Python Programing Language. Jupyter Notebook is integreted powerfull tood provided by Anaconda Open Source. It is best tool for implimation of Machine Learning Algos, Data Analytics or Cleaning operations and Data Science Model Development.

Python also have vast varaites of Library for Machine Learning, Visualisation, Data Cleaning, etc.

We've used Pandas, Numpy, Matplotlib, Seaborn and Sklearn library in our project for various operations.

# 
## Project Insights :
For the good model fit and accuret prediction we've explore the data and done Univariate Analysis, Bivariate Analysis, Correlation Check. Data type check and take dummies.

### Bivariate Analysis :
We've check and learn that which type of occupations have more chances to subscribe our term insurance policy.

![Job vs Target Var](https://user-images.githubusercontent.com/108011984/224013187-67855495-0211-4593-a155-04faf6702287.png)


### Correlation :
We've check correlation between differant variables. We can see here Duration of Call is Highly correlated to our target variable.

![Corelation](https://user-images.githubusercontent.com/108011984/224006874-338b80e4-5aeb-41b8-a2e1-5cad380d5f83.png)


We've split our dataset into 80:20 ratio for train and test purpose to fit into our various Machine Learning Models.

Then we've use 'Logistic Regression Model', 'Decision Tree Model' and 'K Neighbors Classifier Model' and check it's Accuracy Score and check our evaluation metrix AUROC Score.


## Result :

We've get:
	
![image](https://user-images.githubusercontent.com/108011984/224009909-541c8120-fcd7-4c49-b790-10c2a6f9e47a.png)

#### So We'll use the 'Decision Tree Classifier' Model for our predictions. It'll give us accurete and our evalatution metrix 0.7 abide predicted output.

#### Our company can run cost effective and time redusing tele marketing campaign by firstly prioritize potential client from our predicted output and utilse human resourses according to it.


![ROC](https://user-images.githubusercontent.com/108011984/223997228-a643c99c-a52d-4159-8ec1-4a8f64fc0366.png)

