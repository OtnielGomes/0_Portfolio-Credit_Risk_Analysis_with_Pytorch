<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a id="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/OtnielGomes/0_Portfolio-Credit_Risk_Analysis_with_Pytorch">
    <img src="images/logo.jpg" alt="Logo" width="200" height="100">
  </a>

<h3 align="center"> Credit Risk Analysis - Lending Club </h3>

  <p align="center">
    Classification of requested loans using Pytorch as the main classification model
    <br />
    <a href="https://github.com/OtnielGomes/0_Portfolio-Credit_Risk_Analysis_with_Pytorch"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/OtnielGomes/0_Portfolio-Credit_Risk_Analysis_with_Pytorch">View Demo</a>
    ·
    <a href="https://github.com/OtnielGomes/0_Portfolio-Credit_Risk_Analysis_with_Pytorch/issues/new?labels=bug&template=bug-report---.md">Report Bug</a>
    ·
    <a href="https://github.com/OtnielGomes/0_Portfolio-Credit_Risk_Analysis_with_Pytorch/issues/new?labels=enhancement&template=feature-request---.md">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation-of-librarys">Installation of librarys</a></li>
      </ul>
    </li>
    <li><a href="#the-project">The Project</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

<br />
<div align="center">
  <a href="https://github.com/OtnielGomes/0_Portfolio-Credit_Risk_Analysis_with_Pytorch">
    <img src="images/logoLC.jpeg" alt="Logo Lending Club" width="700" height="350">
  </a>
</div>

# Description:

* This project will be built and implemented using the **Azure Databricks** environment, where classifiers will be built with neural network/machine learning models that will seek to predict whether a loan will be paid or not. The basis of the project will be a PyTorch model that will classify the requested loans. In the final model, a classifier will be created that will use the selected model together with some variables and information from the loan applicant to make the final classification, where the loans will be classified into 4 stages of default risk. According to the defined parameters, the classifier will decide whether the loan should be approved or rejected immediately, or if there is the possibility of a reassessment by the institution's stakeholders.

* In this project, I will work with a dataset taken from Kaggle, where I will perform a credit risk analysis. The data provided comes from LendingClub, a financial services company based in San Francisco, California. LendingClub was the first peer-to-peer lending platform to register its offerings as securities with the Securities and Exchange Commission (SEC) and to offer loan trading on a secondary market. The company offers personal loans of up to $40,000, with terms ranging from 24 to 60 months, and operates entirely online, with no physical branches.

* In this project, I will apply the CRISP-DM method, which follows the following steps:

  * 1-**Business understanding**:
  
    What does the business need?
  
  * 2-**Data understanding**:
  
    What data do we have/need? Is it clean?
  
  * 3-**Data preparation**:
  
    How do we organize the data for modeling?
  
  * 4-**Modeling**:
  
    What modeling techniques should we apply?
  
  * 5-**Evaluation**:
  
    What best meets the business objectives?
  
  * 6-**Implementation**:
  
    How do stakeholders access the results?

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With
* [![Databricks][Azure Databricks]][Azure Databricks-url]
* [![Language Python][Python]][Python-url]
* [![Apache][Apache Spark]][Apache Spark-url]
* [![PD][Pandas]][Pandas-url]
* [![NP][NumPy]][NumPy-url]
* [![Matplot][Matplotlib]][Matplotlib-url]
* [![Ploty Lib][Plotly]][Plotly-url]
* [![Torch][PyTorch]][PyTorch-url]
* [![Sklearn][scikit-learn]][scikit-learn-url]
* [![Ray][Ray Tune]][Ray Tune-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

### Prerequisites

* Data Bricks - This project was developed in the Databricks environment, so the entire project structure is compatible with AzureDatabricks and Databricks Community. Below I will leave the link to create an account in the Databricks Community where it is free and at no cost and you will be able to run a copy of this project perfectly.
Link for create acount :

* [![Databricks CM][Azure Databricks CM]][Azure Databricks CM-url]

* ##### Now that your account is created, you will need to create a cluster in DataBricks. Below is the step-by-step guide to creating the cluster.

* ###### Step-by-Step Guide to Creating a Cluster in Databricks

   1-**Access Databricks**:
    - Log in to your Databricks account.

   2-**Navigate to the Clusters Section**:
    - In the side menu, click on **Compute** (or **Clusters**).

   3-**Create a New Cluster**:
    - Click on the **Create Cluster** button.

   4-**Configure the Cluster**:
    - **Cluster Name**: Give your cluster a name.
    - **Cluster Mode**: Choose the cluster mode (Standard, High Concurrency, etc.).
    - **Databricks Runtime Version**: Select the version of Databricks Runtime you want to use.
    - **Node Type**: Choose the node type (virtual machine) for the workers and the driver. - **Autoscaling**: Enable or disable autoscaling. If enabled, set the minimum and       maximum number of nodes.
    - **Worker Nodes**: Set the number of worker nodes.
    - **Driver Node**: Configure the driver node if necessary.
    - **Version used in this project**: 15.4 LTS (includes Apache Spark 3.5.0, Scala 2.12)

   5-**Advanced Settings (Optional)**:
    - **Libraries**: Add libraries that the cluster should load when starting.
    - **Spark Configurations**: Add Spark-specific configurations.
    - **Environment Variables**: Set environment variables if necessary.

   6-**Create the Cluster**:
    - After configuring all options, click **Create Cluster**.

  * #### Additional Resources

    * **Official Documentation**: See the official Databricks documentation for more details and advanced options: [Click here](https://learn.microsoft.com/en-us/azure/databricks/scenarios/quickstart-create-databricks-workspace-vnet-injection).


### Installation of librarys

* Install Libraries to the Cluster:

    * After creating the cluster, click on the cluster name to open its settings.

    *  Go to the Libraries tab.

    * Click Install New.

    * Choose the library source (e.g., PyPI, Maven, CRAN, DBFS, etc.).

    * Follow the instructions to install the desired library. For example, to install a library from PyPI, enter the package name and click Install.

* Librares:
  
  1-threadpoolctl: **PyPI**
     ```sh
     threadpoolctl==3.5.0
     ```
  2-spark-excel_2.12:0.14.0: **Marven**
     ```sh
     com.crealytics:spark-excel_2.12:0.14.0
     ```
  3-scikit-learn: **PyPI**
     ```sh
     scikit-learn==1.5.2
     ```
  4-category_encoders: **PyPI**
     ```sh
     category_encoders==2.6.3
     ```
  5-torch: **PyPI**
     ```sh
     torch==2.5.1
     ```
  6-torchmetrics: **PyPI**
     ```sh
     torchmetrics==1.4.2
     ```
  7-xgboost: **PyPI**
     ```sh
     xgboost==2.1.0
     ```
  8-ray[tune]: **PyPI**
     ```sh
     ray[tune]==2.38.0
     ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## The Project

# 1-Business Understanding

## Lending Club

LendingClub is a company that specializes in providing online loans, which further reinforces the need for an accurate assessment during the analysis of the approval of requested loans.

During a loan application, the company makes only two decisions: grant the loan to the applicant or block the release of the loan. This decision is based on the data present in the registry and the information provided by the potential borrower.

We will only use the records with the following final payment statuses:

* Fully Paid
* Downloaded

The other payment statuses have not yet had final payment completion because they have not yet been completed, so there is no possibility of classifying them.

#### What is the objective of this project?

* A machine learning model will be created that seeks to make predictions that during the loan application will indicate whether the borrower will be a good payer or not.

* The main objective is to create analyses that use only the information collected at the time of the loan application. The model focuses on preventing the release of loans to potentially defaulting borrowers, using only the variables available at the time of the request.

* I will seek to generate several insights so that we have information about the institution's objective, which is to reduce unpaid loans and potential losses in relation to recent years.

#### To deal with default, we have some possible solutions:

* Do not release loans classified as risky loans that will potentially not be paid.

* If released, charge a higher interest rate for these cases.

#### For loans classified as low-risk loans that will potentially be fully paid, we can consider:

* In addition to releasing the loans, increase the loan amount in these cases.

* Reduce the interest rate, aiming to improve the relationship with the target customer and increase the company's profitability with higher-value loans.

* Offer more services to this borrower.

# 2-Data Understanding

## The dataset

**We have records from 12-2006 to 12-2015 with information about the payment history of this institution's customers**

**Data file**: - loan.csv

**Data dictionary**: - LoanStats tab in LCDataDictionary.xlsx

**Target dependent variable**: - 'loan_status'

**Source** : https://www.kaggle.com/datasets/ranadeep/credit-risk-dataset/data?select=loan

## Adjusting the dataset for the project

* Before starting the analyzes and training the models, the data set will be adjusted to the proposal that will be the objective of this project. The objective is to create one or more models capable of predicting whether the borrower will pay all the loan installments or become a defaulter, failing to pay the loan.

* From now on, the dataset will only be separated with records that correspond to loans that have already been closed. The loan_status variable allows you to define the payment statuses that characterize these loans. 

* They are: 

* **Fully Paid**

* **Charged Off**

##### Note:

The payment statuses below will not be used because they do not comply with the institution's credit policy. Since this is a credit risk analysis model, it is important to build it now so that it adapts to the loan requests that will be made by the institution in the future.

* Does not meet the credit policy. Status:Fully Paid

* Does not meet the credit policy. Status:Charged Off

<br />
<div align="left">
  <a href="https://github.com/OtnielGomes/0_Portfolio-Credit_Risk_Analysis_with_Pytorch">
    <img src="images/status_payments_initial.png" alt="Status Payments Initial" width="700" height="400">
  </a>
</div>
<br />


## Classifying variables:

#### Concepts for Classification of variables according to statistics:

**Quantitative or numerical variables**:

* *Discrete*: only take integer values

* *Continuous*: assumes any value in the range of real numbers

**Qualitative or categorical variables**:

* *Nominals*: when categories do not have a natural order

* *Ordinals*: when categories can be ordered.

```
  # Categorical Variables
  
  categorical_nominals =  [
     'verification_status', 'emp_title', 'home_ownership', 'purpose', 'title', 'addr_state', 'initial_list_status', 'loan_status', 
  
  ]
  
  categorical_ordinals = [ 
     'grade', 'sub_grade', 'term', 'emp_length', 
  ]
  
  # Numerical Variables
  
  numerical_discrete = [
      'delinq_2yrs', 'earliest_cr_line', 'inq_last_6mths', 'open_acc', 'pub_rec', 'total_acc', 'acc_now_delinq', 'collections_12_mths_ex_med', 'issue_d'
  ]
  
  
  numerical_continuous = [
     'loan_amnt', 'funded_amnt', 'int_rate', 'installment', 'annual_inc', 'dti', 'revol_bal', 'revol_util', 'tot_coll_amt', 'tot_cur_bal', 'total_rev_hi_lim',
  
  ]
```
<br />
<div align="left">
  <a href="https://github.com/OtnielGomes/0_Portfolio-Credit_Risk_Analysis_with_Pytorch">
    <img src="images/classification_variables.png" alt="Classification Variables" width="700" height="500">
  </a>
</div>
<br />

# 3-Data Preparation

* In this initial step, I will clean the data. We have a lot of invalid data. Initially, I will start by checking the data typing: continuous numeric data will be of type double, and discrete numeric data will be of type integer. This approach will already do a great deal of removing invalid values ​​from the numeric columns. In addition, categorical variables will be checked according to their respective valid categories. 

* Initially, all invalid values ​​will be marked as null, so that at the end of the analysis, I can decide whether to remove them or fill them with some data imputation technique.
### Note:

* The initial data cleaning was performed with the function above.

* **Discrete numeric variables**:

  * These variables were converted to the **'Integer'** type, and the data was filtered in which the values ​​present in the column that were not of the 'Integer' type were removed and filled as null. For example, if a value in a column was 2.3, this value would be considered null, taking into account that discrete variables cannot be partitioned into real numbers.

* **Continuous numeric variables**:

  * They were also converted to their corresponding type. Therefore, the data was filtered in which the values ​​present in the column that were not of the **'Double'** type were removed and filled as null. This approach has already managed to solve the problem of string values ​​that were present in the numeric columns.

* **Categorical/dummy variables**:

  * The data was filtered using the dictionary with valid categories for each variable, and if there were values ​​that were outside these parameters, they were removed and filled in as null.

## EDA 

#### Next steps:

#### Feature selection:

* In this step, I will select features using two approaches:

  * **First**, I will consider the **context** of each of the variables and their importance in the records of this dataset.

  * **Second**, I will evaluate the correlation and relationship of the features with the target variable, which is **loan_status**.

* Based on these points and concepts, I will choose the features that add value to the solution of this problem.

* To calculate the correlation between the columns, I will define a function to index the categorical columns. I will use the correlation to check for numerical variables, while for categorical variables I will use the p-value along with the chi-square (chi2) test.

#### Splitting the training and testing data

* From here on, all the analyses will be based on our training dataset, which will be approximately 80% of the total dataset. I will choose to separate from this point on to avoid leaking **test data**, since this data cannot be influenced by the analysis or data modeling that will be applied to the training data.

* Since this is a credit risk analysis, it is important to consider that the division of the data must take into account the chronological order of the records. This is important to verify the performance of the model with past data (loans that were used for training) in relation to future data (loans that will be requested in the future).

* In other words, this step is important to verify how well the model trained with past data can predict the default of credit applicants at a future point in time.

* Then I will use the **mo_issue_d** variable to classify the records in chronological order, and the division of our data is as follows:

  * **trainset**: Approximately 80% of the records being the oldest and in chronological order.

  * **testset**: Approximately 20% of the records being the newest and in chronological order.

* I will make a small adjustment so that the data is distributed more organically, I will be looking for a margin where we have a time point between the training data and another for the test data. Therefore, with this adjustment we will not have loans with the same number of months in the training and testing data.

### Separating training and test data

```
  # Sorting the data
sorted_dataset = df
sorted_dataset = sorted_dataset.orderBy('mo_issue_d', ascending = False)

# Creating an id for each record in an orderly manner
sorted_dataset = sorted_dataset.withColumn('index', F.monotonically_increasing_id()) 

sorted_dataset.select('index', 'loan_amnt', 'loan_status', 'mo_issue_d') \
    .limit(10) \
    .display()
```
<br />
<div align="left">
  <a href="https://github.com/OtnielGomes/0_Portfolio-Credit_Risk_Analysis_with_Pytorch">
    <img src="images/sorting_data.png" alt="Sorting Data" width="1000" height="400">
  </a>
</div>
<br />

#### Looking for a margin for data division

```
# Calculating the limit for division
  
  total_data = sorted_dataset.count()
  
  train_size = int(total_data * 0.8)
  
  # Partitioning the data
  # trainset
  train_m = sorted_dataset.filter(F.col('index') < train_size)
  
  # testset
  test_m = sorted_dataset.filter(F.col('index') >= train_size)
```
#### Train margin

```
  train_m.select('mo_issue_d').describe().display()
```
<br />
<div align="left">
  <a href="https://github.com/OtnielGomes/0_Portfolio-Credit_Risk_Analysis_with_Pytorch">
    <img src="images/train_m.png" alt="Train Margin" width="1000" height="250">
  </a>
</div>
<br />

#### Test margin

```
  test_m.select('mo_issue_d').describe().display()
```
<br />
<div align="left">
  <a href="https://github.com/OtnielGomes/0_Portfolio-Credit_Risk_Analysis_with_Pytorch">
    <img src="images/test_m.png" alt="Test Margin" width="1000" height="250">
  </a>
</div>
<br />

#### Final parameters for splitting training and test data:

* I will be considering the number of months as 17 with a parameter to separate the training and test data.

##### For the training data, it will be as follows:

* **training_set**: from **18** months to **102** months of loan time in relation to the maximum data collection period.

* There will be records of loans from **1 year and 6 months to loans of 8 years and 6 months**.

##### For the test data, it will be as follows:

* **test_set**: from **0** months to **17** months of loan time in relation to the maximum data collection period

* There will be records of loans from **0 months to loans of 1 year and 5 months**.

### Checking payments status train data and test data:

<br />
<div align="left">
  <a href="https://github.com/OtnielGomes/0_Portfolio-Credit_Risk_Analysis_with_Pytorch">
    <img src="images/train_set_status.png" alt="Train set status" width="700" height="400">
  </a>
</div>
<br />

<br />
<div align="left">
  <a href="https://github.com/OtnielGomes/0_Portfolio-Credit_Risk_Analysis_with_Pytorch">
    <img src="images/test_set_status.png" alt="Test set status" width="700" height="400">
  </a>
</div>
<br />

## Analyzing problems and possible solutions

### With this data, what are the impacts generated by the institution through the loans granted?

<br />
<div align="left">
  <a href="https://github.com/OtnielGomes/0_Portfolio-Credit_Risk_Analysis_with_Pytorch">
    <img src="images/total_loans.png" alt="Total loans" width="700" height="500">
  </a>
</div>
<br />

### Insight:

It can be seen that, in total, loans worth **US$ 3,419,985,650.00** were granted. Of these, **US$ 2,763,446,275.00** was paid in full, while **US$ 656,539,375.00** was lost in part or in full.

### So, what is the consequence of a wrong classification when granting a loan?

If we consider that the loans that were considered lost by Lending Club, if they were declined at the time of application, a **loss** of approximately **US$ 656,539,375.00** could have been avoided.

### What if there was the opposite situation?

If loans that were considered **paid** by Lending Club at the time of application were **unfairly denied**? Because they presented a risk of fraud to the institution. What would be the consequences of this scenario?

<br />
<div align="left">
  <a href="https://github.com/OtnielGomes/0_Portfolio-Credit_Risk_Analysis_with_Pytorch">
    <img src="images/total_int_rate.png" alt="Total int rate" width="900" height="500">
  </a>
</div>
<br />

### Insight:

It is possible to note that loans that were **fully paid** generate a gross interest amount of **US$ 380,373,134.10**. If these loans were denied, this would be a parameter to quantify the **financial loss** that would be caused to the institution.

## Cheking numerical discrete variables

### Note:

* To analyze the discrete variables, I chose to separate them, as some variables, due to the nature of their distribution, are more suitable for visualization through histoplots, while others are more appropriate for countplots.

<br />
<div align="left">
  <a href="https://github.com/OtnielGomes/0_Portfolio-Credit_Risk_Analysis_with_Pytorch">
    <img src="images/count_discret_variables.png" alt="Count discret variables" width="900" height="500">
  </a>
</div>
<br />

<br />
<div align="left">
  <a href="https://github.com/OtnielGomes/0_Portfolio-Credit_Risk_Analysis_with_Pytorch">
    <img src="images/hist_discret_variables.png" alt="Histogran discret variables" width="900" height="350">
  </a>
</div>
<br />

## Cheking numerical continuos variables

<br />
<div align="left">
  <a href="https://github.com/OtnielGomes/0_Portfolio-Credit_Risk_Analysis_with_Pytorch">
    <img src="images/hist_continuos_variables.png" alt="Histogran continuos variables" width="900" height="1100">
  </a>
</div>
<br />

## Cheking categorical  variables

<br />
<div align="left">
  <a href="https://github.com/OtnielGomes/0_Portfolio-Credit_Risk_Analysis_with_Pytorch">
    <img src="images/count_cat_variables.png" alt="Count cat variables" width="900" height="1100">
  </a>
</div>
<br />


<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Cheking the locations of the institution's customers

<br />
<div align="left">
  <a href="https://github.com/OtnielGomes/0_Portfolio-Credit_Risk_Analysis_with_Pytorch">
    <img src="images/fully_paid_regions.png" alt="Fully paid regions" width="900" height="500">
  </a>
</div>
<br />

<br />
<div align="left">
  <a href="https://github.com/OtnielGomes/0_Portfolio-Credit_Risk_Analysis_with_Pytorch">
    <img src="images/charged_off_regions.png" alt="Charged off regions" width="900" height="500">
  </a>
</div>
<br />

## Cheking correlations variables

<br />
<div align="left">
  <a href="https://github.com/OtnielGomes/0_Portfolio-Credit_Risk_Analysis_with_Pytorch">
    <img src="images/correlation_variables.png" alt="Correlation variables" width="900" height="500">
  </a>
</div>
<br />

## Creating new features
* This dataset has some data that are not viable for training a machine learning model, due to the fact that they **have no relationships with the target variable** and, in some cases, due to the **lack of diversity in the numbers**, since most of the values ​​are **zero**.

* We also have some variables with a very large number of null data that, contextually, would be of great value for our analyses, but because they **do not have even 50% of the valid data**, they were not added to the analyses and training. Due to these facts and characteristics present in this dataset, I will choose to explore the data used in the analyses a little more and look for new possibilities and combination of values ​​for the existing variables.

* Therefore, I will explore new possibilities with our data and check the possibility of combining some characteristics to generate new variables, in order to add information to our data.

### Real income
I will be calculating the annual income considering the **DTI** (debt to equity ratio). I will subtract the borrower’s debts and consider only his/her net salary, with debts and liabilities already discounted.

Dti formula:

$$ DTI = {\frac{\text{ Total Debts }}{\text{ Total Income  }}{\text{ x 100 }}} $$

Real Income formula:

$$ Real Income = {\text{Annual Income - }} \frac{\text{( Annual Income x DTI )}}{\text{100}}$$

```
  data_corr = data_corr.withColumn('real_income', F.round((F.col('annual_inc') - (F.col('annual_inc') * F.col('dti')) / 100), 2))
```

### Ability to pay
I am creating a new column that will interact with the previously created column called **real_income**. This new column will calculate the impact of the monthly installments on the borrower’s monthly income. The calculation will be done as follows: first, I will divide the **real_income by 12**, converting it from annual income to monthly income. Then, I will apply a formula similar to the ‘DTI’ (debt-to-income) calculation to get the impact of the installment on the borrower’s monthly income. I will do this by **dividing the installment amount by the real_income and then multiplying it by 100**. This way, we will get the impact of the installment on the borrower’s monthly income as a percentage.

Ability To Pay formula:

$$ Ability To Pay = \frac{\text{Installment}} {\frac{\text{Real Income }}{\text{12 Months}}}{\text{ x 100}}$$
```
  data_corr = data_corr.withColumn('ability_to_pay', F.round(((F.col('installment') / (F.col('real_income') / 12)  * 100 )), 2))
```
### Expenses credit rotative vs Income

The **revol_bal** variable: refers to the borrower's revolving balance, which is the amount unpaid at the end of the credit card billing cycle. In other words, it is the amount of debt that remains after the minimum or partial payment of a credit card bill.

Although our **revol_bal** variable has shown a low correlation with our payment status, it provides us with very important information to assess the financial health of our borrowers. With this, it was possible to create a new variable that calculates the borrower's monthly income and then the percentage of monthly income committed to the borrower's current revolving balance.

* I then created a new variable that classifies this as follows:

* **A**: borrowers with 50% or less of their monthly income committed to their current revolving balance.

* **B**: borrowers with more than 50% to 120% of their monthly income committed to their current revolving balance.

* **C**: borrowers with more than 120% to 300% of their monthly income committed to their current revolving balance.

* **D**: borrowers with more than 300% of their monthly income committed to their current revolving balance.

Expenses credit rotative vs Income formula:

$$ Expen Cr Inc = \frac{\text{Revol Bal}} {\frac{\text{Anual Income }}{\text{12 Months}}}{\text{ <= Income Commitment Limit }}$$

```
  data_corr = data_corr.withColumn('mo_income', F.round(F.col('annual_inc') / 12, 2)) \
    .withColumn('expen_cr_inc', F.when((F.round(F.col('revol_bal') / (F.col('mo_income')), 2) <= 0.5) , 'A').otherwise(None)) \
    .withColumn('expen_cr_inc', F.when((F.col('revol_bal') / (F.col('mo_income')) > 0.5) & 
                                       (F.col('revol_bal') / (F.col('mo_income')) <= 1.2), 'B').otherwise(F.col('expen_cr_inc'))) \
    .withColumn('expen_cr_inc', F.when((F.col('revol_bal') / (F.col('mo_income')) > 1.2) & 
                                       (F.col('revol_bal') / (F.col('mo_income')) <= 3), 'C').otherwise(F.col('expen_cr_inc'))) \
    .withColumn('expen_cr_inc', F.when(F.col('revol_bal') / (F.col('mo_income')) > 3 , 'D').otherwise(F.col('expen_cr_inc')))
```

### Score_cr

The **score_cr** variable is based on the rules of the FICO Score. This score takes into account some information about the borrower's financial health and generates a score.

*Here are the FICO Score scoring rules:*

* **Payment history (35%)**
  * The first thing any lender wants to know is whether you have paid previous credit accounts on time. This helps the lender figure out how much risk they will take on granting you credit. This is the most important factor in a FICO score.

  * *Columns in the dataset*: 'delinq_2yrs', 'pub_rec', 'tot_coll_amt'.

* **Amounts owed (30%)**
  * Having credit accounts and owing money on them does not necessarily mean you are a high-risk borrower with a low FICO score. However, if you’re using too much of your available credit, it could indicate that you’re overextended — and lenders may interpret this to mean that you’re at higher risk of defaulting.

  * *Columns in the dataset*: 'expen_cr_inc', 'revol_util', 'dti'

* **Length of credit history (15%)**
  * In general, having a longer credit history is positive for your FICO Scores, but it’s not necessary for a good credit score. How long ago specific credit accounts were established. How long it’s been since you used certain accounts

  * *Column in the dataset*: 'mo_earliest_cr_line'

* **Credit mix (10%)**
  * FICO Scores will consider your mix of credit cards, retail accounts, installment loans, finance company accounts, and mortgage loans. Don’t worry, you don’t need to have one of each. 

  * *Column in the dataset*: 'total_acc'

* **New credit (10%)**
  * Research shows that opening multiple credit accounts in a short space of time poses a greater risk – especially for people who don't have a long credit history.

  * *Columns in the dataset*: 'open_acc', 'inq_last_6mths'

```
  # Total points: 1000
  # Payment history 35% of points: 350.0
  # Amounts due 30% of points: 300.0
  # Length of credit history 15% of points: 150.0
  # Credit mix 10% of points: 100.0
  # New credit 10% of points: 100.0

  # Payment history: 350 points divided by 3 features('delinq_2yrs', 'collections_12_mths_ex_med', 'tot_coll_amt') = 166.66.
  weigth_pay_history = (350 / 3)

  # Amounts due: 350 points divided by 3 features('expen_cr_inc', 'revol_util', 'dti') = 100.
  weigth_amnt_due = (300 / 3)
  
  # Length of credit: 150 points only feature('credit_time') = 150.
  weigth_length_cr = 150
  
  # Credit mix: 100 points only feature('total_acc') = 100.
  weigth_cr_mix = 100
  
  # New credit: 100 points divided by 2 features('open_acc', 'inq_last_6mths') = 50.
  weigth_new_cr = (100 / 2)

  data_corr = data_corr.withColumn('score_cr', F.lit(0)) \
      .withColumn('score_cr', F.when(F.col('delinq_2yrs') == 0, 
                                     F.col('score_cr') + (weigth_pay_history)).otherwise(F.col('score_cr'))) \
      .withColumn('score_cr', F.when(F.col('delinq_2yrs') == 1, 
                                     F.col('score_cr') + (weigth_pay_history / 2)).otherwise(F.col('score_cr'))) \
      .withColumn('score_cr', F.when(F.col('pub_rec') == 0, 
                                     F.col('score_cr') + (weigth_pay_history)).otherwise(F.col('score_cr'))) \
      .withColumn('score_cr', F.when(F.col('pub_rec') == 1, 
                                     F.col('score_cr') + (weigth_pay_history / 2)).otherwise(F.col('score_cr'))) \
      .withColumn('score_cr', F.when(F.col('tot_coll_amt') == 0, 
                                     F.col('score_cr') + (weigth_pay_history)).otherwise(F.col('score_cr'))) \
      .withColumn('score_cr', F.when(F.col('tot_coll_amt') == 1, 
                                     F.col('score_cr') + (weigth_pay_history / 2)).otherwise(F.col('score_cr'))) \
      .withColumn('score_cr', F.when(F.col('expen_cr_inc') == 'A', 
                                     F.col('score_cr') + (weigth_amnt_due)).otherwise(F.col('score_cr'))) \
      .withColumn('score_cr', F.when(F.col('expen_cr_inc') == 'B', 
                                     F.col('score_cr') + (weigth_amnt_due / 2)).otherwise(F.col('score_cr'))) \
      .withColumn('score_cr', F.when(F.col('expen_cr_inc') == 'C', 
                                     F.col('score_cr') + (weigth_amnt_due / 3)).otherwise(F.col('score_cr'))) \
      .withColumn('score_cr', F.when(F.col('expen_cr_inc') == 'D', 
                                     F.col('score_cr') + (weigth_amnt_due / 4)).otherwise(F.col('score_cr'))) \
      .withColumn('score_cr', F.when(F.col('dti') <= 10, 
                                     F.col('score_cr') + (weigth_amnt_due)).otherwise(F.col('score_cr'))) \
      .withColumn('score_cr', F.when(((F.col('dti') <= 20) & ( F.col('dti') > 10)), 
                                     F.col('score_cr') + (weigth_amnt_due / 2)).otherwise(F.col('score_cr'))) \
      .withColumn('score_cr', F.when(((F.col('dti') <= 30) & (F.col('dti') > 20)), 
                                     F.col('score_cr') + (weigth_amnt_due / 3)).otherwise(F.col('score_cr'))) \
      .withColumn('score_cr', F.when(F.col('dti') > 30, 
                                     F.col('score_cr') + (weigth_amnt_due / 4)).otherwise(F.col('score_cr'))) \
      .withColumn('score_cr', F.when(F.col('revol_util') <= 30, 
                                     F.col('score_cr') + (weigth_amnt_due)).otherwise(F.col('score_cr'))) \
      .withColumn('score_cr', F.when(((F.col('revol_util') <= 60) & ( F.col('revol_util') > 30)), 
                                     F.col('score_cr') + (weigth_amnt_due / 2)).otherwise(F.col('score_cr'))) \
      .withColumn('score_cr', F.when(((F.col('revol_util') <= 90) & (F.col('revol_util') > 60)), 
                                     F.col('score_cr') + (weigth_amnt_due / 3)).otherwise(F.col('score_cr'))) \
      .withColumn('score_cr', F.when(F.col('revol_util') > 90, 
                                     F.col('score_cr') + (weigth_amnt_due / 4)).otherwise(F.col('score_cr'))) \
      .withColumn('score_cr', F.when(F.col('mo_earliest_cr_line') > 150, 
                                     F.col('score_cr') + (weigth_length_cr)).otherwise(F.col('score_cr'))) \
      .withColumn('score_cr', F.when(F.col('mo_earliest_cr_line') <= 150, 
                                     F.col('score_cr') + (weigth_length_cr / 2)).otherwise(F.col('score_cr'))) \
      .withColumn('score_cr', F.when(F.col('total_acc') > 20, 
                                     F.col('score_cr') + (weigth_cr_mix)).otherwise(F.col('score_cr'))) \
      .withColumn('score_cr', F.when(F.col('total_acc') <= 20, 
                                     F.col('score_cr') + (weigth_cr_mix / 2)).otherwise(F.col('score_cr'))) \
      .withColumn('score_cr', F.when(F.col('open_acc') <= 10, 
                                     F.col('score_cr') + (weigth_new_cr)).otherwise(F.col('score_cr'))) \
      .withColumn('score_cr', F.when(F.col('open_acc') > 10, 
                                     F.col('score_cr') + (weigth_new_cr / 2)).otherwise(F.col('score_cr'))) \
      .withColumn('score_cr', F.when(F.col('inq_last_6mths') == 0, 
                                     F.col('score_cr') + (weigth_new_cr)).otherwise(F.col('score_cr'))) \
      .withColumn('score_cr', F.when(F.col('inq_last_6mths') == 1, 
                                     F.col('score_cr') + (weigth_new_cr / 2)).otherwise(F.col('score_cr'))) \
      .withColumn('score_cr', F.round(F.col('score_cr'), 2))
```

### Viewing the new features

<br />
<div align="left">
  <a href="https://github.com/OtnielGomes/0_Portfolio-Credit_Risk_Analysis_with_Pytorch">
    <img src="images/count_news_variables.png" alt="Count news variables" width="500" height="300">
  </a>
</div>
<br />

<br />
<div align="left">
  <a href="https://github.com/OtnielGomes/0_Portfolio-Credit_Risk_Analysis_with_Pytorch">
    <img src="images/hist_news_variables.png" alt="Histogran news variables" width="900" height="300">
  </a>
</div>
<br />



## Final data processing

* **Irrelevant data**:

  * I will remove from the training and test sets the columns that were excluded according to the above analyses.

* **Null or missing data**:

  * **Numeric data**: The numeric data from the columns:

    * revol_util

    * tot_coll_amt

    * tot_cur_bal

    * total_rev_hi_lim

  * will be imputed using the median, a sensible choice for filling in missing data, especially considering the presence of outliers in the numeric data in this set.

  * **Categorical data**: We have no missing values ​​in our categorical columns.

  * **Note**:

    I chose to impute the null data to preserve the natural distribution of the data in this dataset.

* **New features**:

  * New columns will be created right after the null data is discarded, preventing these new columns from containing null data.

* **Correlated variables**:

  * These columns will be removed from our training data, so that there is no noise caused by correlation in our training since they are correlated with the new features:

    * revolution_bal

    * annual_inc

  * **loan_amnt x installment**:


  * I will choose to remove the **installment** column and keep the **loan_amnt** column, since this column has a stronger relationship with the payment statuses.

# 4-Modeling

* **Categorical Variables**: 
  
  * For ordinal categorical variables, I will use the Ordinal Encoder. For nominal variables, the Target Encoder will be applied, with the aim of not increasing the dimensionality of our data, and also considering that this approach brings us more information for our training data because the variables are encoded according to their distributions in relation to the target variable, which in this case will be the **loan_status**.

* **Numerical Variables**: 
  
  * For numerical data, we will apply the normalization technique using MinMaxScaler. This choice aims to preserve the distribution of the data, considering that our distributions are almost all asymmetric, so opting for MinMaxScaler makes more sense in this context.

  * The decision to use MinMaxScaler also takes into account the fact that our data has a significant amount of outliers. However, these outliers are part of the natural distribution of the institution's data. Therefore, the objective of this choice is to allow the model to learn from this data.

* **Machine learning algorithms that will be used in this project**:

  * The basis of this project is a model with PyTorch, but first, to compare and verify the most suitable models for our data, a model will be created in each of the algorithms below:

  * Random Forest Classifier

  * KNN

  * Logistic Regression

  * XGBoost

  * Next, a network will be created in PyTorch. This network will undergo an initial training, in which we will evaluate the metrics and the results obtained.

* **How will the metrics for the evaluation stage be chosen?**:

  * The metrics that will be considered as a parameter to determine the best model and its effectiveness will be **AUC-ROC** together with **Accuracy**. Since we are dealing with binary classes and we have a minority class, which are the loans classified as unpaid, the accuracy of the model would not be enough to determine whether the model converged adequately with its classifications.

  * Therefore, I will be using the **AUC-ROC** metric as the first criterion as a main parameter to determine the effectiveness of the model. This metric takes into account the correct classification of the positive and negative classes, since in a dataset where we have an imbalance in the classes, it is common and natural to expect that the model has a tendency to classify most of the training and testing data with the majority class. Therefore, we will use this metric as a fundamental parameter for the evaluation and analysis of our models, so that we have a good control over false positives and false negatives, in order to reduce them as much as possible.

  * In the background, I will use the accuracy of the model to consider whether there is good predictability of the model with training, validation and testing data.

* **Hypertune | Finetune**:

  * After this initial training, we will **hypertune** the model, adjusting the hyperparameters and the number of neurons in the hidden layers.

  * Later, we will **finetune**, adjusting the learning level per epoch of the model.

* **Test data**

  * Finally, we will move on to the model evaluation stage, in which we will check its performance on the test data.

## Separating features and labels 

```
  train_data['loan_status'] = train_data['loan_status'].map({'Fully Paid': 0, 'Charged Off': 1}).astype(int)
  test_data['loan_status'] = test_data['loan_status'].map({'Fully Paid': 0, 'Charged Off': 1}).astype(int)
```
```
  # Train
  X_train = train_data.drop(columns = ['loan_status']) 
  y_train =  train_data['loan_status'].copy()
  
  # Test
  X_test = test_data.drop(columns = ['loan_status']) 
  y_test =  test_data['loan_status'].copy()
```

## Preprocessing

### Categorical Features
```
  # Ordinal features
  ordinal_features = [
       'term', 'sub_grade', 'expen_cr_inc'  
  ]
  # Manual adjustment
  ordinal_emp_length = ['emp_length']
  
  # Nominal Features
  
  nominal_features = ['home_ownership', 'purpose', 'initial_list_status', 'tot_coll_amt', 'delinq_2yrs', 'pub_rec', 'inq_last_6mths',]
```

### Numerical Features
```
  num_features = [
    'loan_amnt', 'int_rate', 'dti', 'open_acc', 'revol_util', 'total_acc','tot_cur_bal', 'total_rev_hi_lim', 'real_income', 'ability_to_pay', 'score_cr',   'mo_earliest_cr_line',
  ]
```

### Preprocessor
```
  # Categorical ordinal
  categorical_ordinal = Pipeline(
      steps = [
          ('ordinal_encoder', OrdinalEncoder()),
          ('min_max_scaler', MinMaxScaler()),
      ]
  )
  # emp_length
  emp_length_ordinal = Pipeline(
      steps = [
          ('ordinal_encoder', OrdinalEncoder(categories = [['0', '1', '2', '3', '4', '5', '6', '7', '8', '9', '10']])),
          ('min_max_scaler', MinMaxScaler()),
      ]
  )
  
  
  # Categorical Nominal
  categorical_nominal = Pipeline(
      steps = [
          ('target_encoder', TargetEncoder(cols = nominal_features)),
          ('min_max_scaler', MinMaxScaler()),
      ]
  )
  
  
  # Column Transformer
  preprocessor = ColumnTransformer(
      transformers = [
          ('ordinal', categorical_ordinal, ordinal_features),
          ('ord_emp_length', emp_length_ordinal, ordinal_emp_length),
          ('target', categorical_nominal, nominal_features),
          ('numerical_features', MinMaxScaler(), num_features),
      ],
      remainder = 'passthrough'
  )
```
## Training models

### Random Forest Classifier

<p align="right">(<a href="#readme-top">back to top</a>)</p>
<!-- ROADMAP -->
## Roadmap

- [ ] Feature 1
- [ ] Feature 2
- [ ] Feature 3
    - [ ] Nested Feature

See the [open issues](https://github.com/OtnielGomes/0_Portfolio-Credit_Risk_Analysis_with_Pytorch/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Top contributors:

<a href="https://github.com/github_username/repo_name/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=github_username/repo_name" alt="contrib.rocks image" />
</a>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Your Name - [@twitter_handle](https://twitter.com/twitter_handle) - email@email_client.com

Project Link: [https://github.com/github_username/repo_name](https://github.com/github_username/repo_name)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* []()
* []()
* []()

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/OtnielGomes/0_Portfolio-Credit_Risk_Analysis_with_Pytorch.svg?style=for-the-badge
[contributors-url]: https://github.com/OtnielGomes/0_Portfolio-Credit_Risk_Analysis_with_Pytorch/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/OtnielGomes/0_Portfolio-Credit_Risk_Analysis_with_Pytorch.svg?style=for-the-badge
[forks-url]: https://github.com/OtnielGomes/0_Portfolio-Credit_Risk_Analysis_with_Pytorch/network/members
[stars-shield]: https://img.shields.io/github/stars/OtnielGomes/0_Portfolio-Credit_Risk_Analysis_with_Pytorch.svg?style=for-the-badge
[stars-url]: https://github.com/OtnielGomes/0_Portfolio-Credit_Risk_Analysis_with_Pytorch/stargazers
[issues-shield]: https://img.shields.io/github/issues/OtnielGomes/0_Portfolio-Credit_Risk_Analysis_with_Pytorch.svg?style=for-the-badge
[issues-url]: https://github.com/OtnielGomes/0_Portfolio-Credit_Risk_Analysis_with_Pytorch/issues
[license-shield]: https://img.shields.io/github/license/OtnielGomes/0_Portfolio-Credit_Risk_Analysis_with_Pytorch.svg?style=for-the-badge
[license-url]: https://github.com/OtnielGomes/0_Portfolio-Credit_Risk_Analysis_with_Pytorch/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/otnielgomes
[product-screenshot]: images/screenshot.png


[Azure Databricks]: https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=Databricks&logoColor=white
[Azure Databricks-url]:  https://azure.microsoft.com/en-us/pricing/purchase-options/azure-account?icid=databricks

[PyTorch]: https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white
[PyTorch-url]: https://pytorch.org

[scikit-learn]: https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white
[scikit-learn-url]: https://scikit-learn.org/stable/

[Apache Spark]: https://img.shields.io/badge/Apache%20Spark-FDEE21?style=flat-square&logo=apachespark&logoColor=black
[Apache Spark-url]: https://spark.apache.org/

[Pandas]: https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white
[Pandas-url]: https://pandas.pydata.org/

[Ray Tune]: https://img.shields.io/badge/Ray-028CF0.svg?style=for-the-badge&logo=Ray&logoColor=white
[Ray Tune-url]: https://docs.ray.io/en/latest/tune/index.html

[Matplotlib]: https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black
[Matplotlib-url]: https://matplotlib.org/

[Plotly]: https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white
[Plotly-url]: https://plotly.com/graphing-libraries/

[NumPy]: https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white
[NumPy-url]: https://numpy.org/

[Python]: https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54
[Python-url]: https://www.python.org/

[Azure Databricks CM]: https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=Databricks&logoColor=white
[Azure Databricks CM-url]: https://community.cloud.databricks.com/
