# Credit Risk Crystal Ball: Predicting Risk with Machine Learning
<img src="https://github.com/NJAimesD/AIAcademyCS/assets/159951082/9249a348-f7f3-46e8-bca0-742d921947ce" width="650" /> 

### Overview and Business Understanding
Credit risk prediction is a crucial process for financial institutions, aiming to assess the likehood of a borrower defaulting on a loan. That way the people not likely to default can more easily access loans with better conditions, while the institutions reduce the risk of financial loss.
There are many techniques to predict credit risk, but Machine Learning (ML) can be used to automate the prediction process, since it learns the patterns associated with a defaulter profile and its use reduces time and resource consumption.
Detecting people with a high risk profile can be a complex task, but still results in a better profit margin for the institution. Also, ML improves the efficiency of the process, and the institution resources can be now used in other areas that require human supervision.

Our team at Deloitte seeks to use different machine learning models to predict the credit risk for different profiles, test them and implement a metric to compare them. Once evaluated, we´ll select the model with the best results, and identify the factors with the highest influence on credit risk for a higher value-add to the client.

#### Benefits

* A streamlined process for approving loans.
* Higher accuracy in the approval process.
* Higher client satisfaction.
* Loan approval fairness, reducing biases


### Description of Data


**Data Source**: Credit Risk Dataset: (https://www.kaggle.com/datasets/laotse/credit-risk-dataset)

**Exploratory analysis**   
We first reviewed all the variables to understand their meaning.

<img src="https://github.com/NJAimesD/AIAcademyCS/assets/159951082/4d96d12d-fde1-47ea-8751-e23fe36e0add" width="500" />


The target variable in this dataset is loan status There are 11 independent variables used for modeling, with a range of 32,581 to 28,638 non-null values. The average age of the sample population is 27 years old, with an average loan amount of around $10,000 and an average credit history of 5.8 years.

The target variable in this case, with 78.3% of values indicating non-default and 21.7% indicating default, is significantly unbalanced, a data balancing technique was needed, specifically, SMOTE, that is an oversampling technique used to balance the class distribution of a dataset by creating synthetic minority class samples..

<img src="https://github.com/NJAimesD/AIAcademyCapstone/assets/159951082/0d3f2174-0525-43d2-af43-126b4d85363d" width="500" /> 


A comparative visual analysis was performed, where we built a correlation matrix for all the variables, 
<img src="https://github.com/NJAimesD/AIAcademyCapstone/assets/159951082/5355d94d-3a12-4858-8514-f387efed3549" width="500" /> 

Checking the variables correlations to the Loan Status, we found that the most correlated variables are  Loan Percent Income, Loan Interest Rate as well as the Loan Grade D, so we would expect this variables to have the greatest impact on the final result.


<img src="https://github.com/NJAimesD/AIAcademyCS/assets/159951082/e342dfb8-4485-408e-a9e2-703e73397373" width="500" /> 

### Data Understanding and Analysis

# Jonathan
<img src="https://github.com/NJAimesD/AIAcademyCS/assets/159951082/625f246c-9091-4396-9d54-768112b26239" width="500" /> 


<img src="https://github.com/NJAimesD/AIAcademyCS/assets/159951082/a180d5ca-ef0f-469d-914c-41f849d4ec6b" width="500" /> 

# Jonathan
<img src="ttps://github.com/NJAimesD/AIAcademyCS/assets/159951082/b14064e7-8d38-4b7b-bcda-69aecbf566a4" width="500" /> 

### Data processing
# Adam
### Models evaluated
# Adam
* Linear Regresion: It is a .....


#### Comparison

![image](https://github.com/NJAimesD/AIAcademyCS/assets/159951082/04e64478-6075-4b03-bec1-a074eed0347c)
![image](https://github.com/NJAimesD/AIAcademyCS/assets/159951082/415fb249-5fd1-4f27-a33f-350fe19e7c1a)

### Optimal model: Random Forest:

![image](https://github.com/NJAimesD/AIAcademyCS/assets/159951082/01096403-d402-4357-8b1f-e48b8c65accc)



