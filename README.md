![](https://ichef.bbci.co.uk/images/ic/976xn//p03lcphh.jpg.webp)

<div align="center">
  
# Household Anxiety and Depression Likelihood Prediction 

</div>

## 📌 Part 1 Project Overview
In an era marked by the rising prevalence of anxiety and depression, the healthcare sector faces the daunting task of addressing mental health concerns among its patients and professionals. Recent global events, such as the COVID-19 pandemic, widespread unemployment, and economic uncertainty, have further magnified these challenges. 
What's often overlooked is the profound influence of household aspects on individual mental well-being.   

This Capstone project is a comprehensive initiative aimed at illuminating the intricate relationship between household factors and mental health within the healthcare sector. It seeks to answer a fundamental question: How do demographic variables, financial status, employment dynamics, childcare availability, medical resources, inflation rates, 
food supply, and vaccination records affect the mental well-being of individuals? 

At its core, this project represents an exploration into the uncharted territory of mental health data science. It is a multi-faceted endeavor encompassing data collection, integration, feature engineering, predictive modeling, and actionable insights. Through advanced data analysis and modeling, it aspires to predict mental health outcomes 
and provide early diagnoses, targeted interventions, and a comprehensive understanding of mental health within the healthcare sector.

The impact of this project reaches far beyond the realm of data analysis. It seeks to reduce the stigma surrounding mental health, improve accessibility to mental health resources, and predict outcomes for the betterment of mental well-being. Ultimately, this project aspires to empower healthcare providers, policymakers, and individuals with 
the tools and knowledge needed to foster a healthier, more resilient society.

### 🎯 1.1 Area of Interest
The primary area of interest of this Capstone project is to investigate the intricate relationship between various household factors and individuals' mental health status within the healthcare sector. We aim to explore how 
demographic factors, financial status, employment status, childcare availability, medical availability, inflation, food supply, vaccination, and other related aspects impact mental well-being. Each of these aspects will be 
dissected into detailed features to enable a deeper exploration. Furthermore, this comprehensive analysis will serve as the foundation for the development of machine learning models, aiming to predict mental health outcomes 
and provide valuable insights for early diagnoses and targeted interventions.

### 🚑 1.2 Problem Statement

This project focuses on predicting the likelihood of anxiety and depression within households. By analyzing a range of household-specific factors, including demographics, financial status, employment, childcare, healthcare 
accessibility, and other related aspects, the goal is to develop machine learning models that can accurately forecast the likelihood of anxiety and depression in household members. These predictive models will provide valuable 
insights for early detection and targeted interventions, ultimately improving the overall mental well-being of households.

### 🎉 1.3 Impacts

The findings of this project hold the potential to make a significant positive impact on both individuals and society at large. By uncovering the intricate web of factors that contribute to Major Depressive Disorder (MDD) and Generalized Anxiety Disorder (GAD), we are in a position to initiate targeted interventions and support systems. The societal and business values that this project can add are multifold. Firstly, addressing mental health issues proactively can lead to a reduction in lost productivity, saving businesses and organizations millions of dollars in healthcare expenditures and productivity losses. Early detection of mental health issues can also translate into substantial cost savings for individuals and healthcare systems. Moreover, the project's insights are integral in promoting healthier, more resilient communities, fostering improved quality of life for individuals and their families. Overall, this research offers a roadmap for more effective mental health strategies, both at the individual and societal levels, with far-reaching implications for the well-being and productivity of our society.

### 🎢 1.4 Proposed Data Science solution
<div align="center">
  
![](https://github.com/coconita526/capstone/blob/main/Proposed%20Data%20Solution%202023-11-09%20at%203.28.50%20PM.png)

</div>

### 📊 1.5 Dataset Description

The dataset utilized for this research was sourced from cdc.gov and originates from the collaborative efforts of the National Center for Health Statistics (NCHS) and the U.S. Census Bureau, known as the Household Pulse Survey. This ongoing survey, in its latest phase, Phase 3.10 (August 23 - September 4), is specifically designed to collect crucial data on the social and economic ramifications of the COVID-19 pandemic on households within the United States. 

To provide accurate and timely weekly estimates, the survey employs an internet-based questionnaire distributed via email and text messages. The dataset draws its sample frame from the Census Bureau Master Address File Data, with randomly selected housing units linked to email addresses or cell phone numbers, and one respondent selected from each housing unit.

In addition to exploring the socio-economic impacts, the survey integrates questions regarding mental health, using a modified version of the Patient Health Questionnaire (PHQ-2) and the Generalized Anxiety Disorder (GAD-2) scale to assess the prevalence of anxiety and depression symptoms within the U.S. population. This dataset, originating from a robust and systematic survey, provides a wealth of information that serves as the foundation for our research into the mental health implications of the pandemic.


## 📌 Part 2 Project Organization
The project is organized into distinct phases and tasks, each with a specific focus and purpose. These phases encompass data collection, preprocessing, modeling, evaluation, and deployment. Below is an overview of the project's organization:

**Data Management**

- Collection and validation of data from the Household Pulse Survey.
- Ensuring data accuracy and consistency through validation.

**Data Processing**

- Handling missing data and addressing outliers.
- Converting categorical variables into numerical representations.

**Data Exploration and Visualization**

- Exploratory data analysis (EDA) to gain insights.

**Feature Engineering**

- Selection of relevant attributes and creation of new features
- Apply techniques like one-hot encoding, label encoding, or ordinal encoding.
  
**Predictive Modeling**

- Development of classification models.
- Utilization of ensemble techniques for improved accuracy.

**Model Evaluation and Validation**

- Employing cross-validation techniques to assess model performance.
- Measuring model accuracy and optimizing hyperparameters.

**Interpretability and Explainability**

- Identification of influential features and provision of model explanations.
  

## 🔔 Part 3 Exploratary Data Analysis

### 3.1 

<div align="center">
  
![]([eda1.png](https://github.com/coconita526/capstone/blob/main/eda1.png))

</div>

In summary, the data reveals that 22% of the individuals have been diagnosed with Generalized Anxiety Disorder (GAD), and 16% have been diagnosed with Major Depressive Disorder (MAD). Additionally, 12% of the individuals have both conditions. These insights underscore the importance of addressing mental health issues and affirm the significance of this study in shedding light on these concerns.


### 3.2
<div align="center">
  
![](https://github.com/coconita526/capstone/blob/main/EDA2.png)

</div>

- 13.3% of Female are diagnosed with both Major Depressive Disorder and Generalized Anxiety Disorder
However, 78.8% of male showed neither of the mental issues. 
- Interestingly, transgender is a group with a very high percentage of 39.4% of being diagnosed with both Major Depressive Disorder and Generalized Anxiety Disorder

### 3.3
<div align="center">
  
![](https://github.com/coconita526/capstone/blob/main/EDA3.png)

</div>

- 25.9% of People who reported very stressful about price are diagnosed with both Major Depressive Disorder and Generalized Anxiety Disorder.
- 93.6 of people who reported not at all stressful about price are diagnosed with neither of the mental issues.

** Conclusions **
- The discovery that nearly half of the participants reported symptoms of Major Depressive Disorder (MDD) and Generalized Anxiety Disorder (GAD) underscores the crucial importance and necessity of our study. These findings highlight the pervasive nature of these mental health challenges in the surveyed population, emphasizing the pressing need for mental health interventions and support systems.

- Our analysis revealed that these symptoms are not uniform across all demographics. Notably, over 70% of transgender individuals reported experiencing both MDD and GAD symptoms, signaling a heightened concern for this vulnerable group. Tailoring mental health initiatives to address the unique challenges faced by specific demographic subgroups is essential in ensuring equitable mental health care.

- The strong correlation between stress levels and fluctuations in prices underscores the profound impact of economic conditions on individuals' mental well-being. This linkage emphasizes the need for government and policy-makers to prioritize economic stability and consider measures to mitigate the impact of price changes on households, ultimately reducing overall stress levels.

- The presence of medical resource shortages has added a layer of mental stress, potentially exacerbating mental health issues. Particularly in the wake of the post-pandemic period, where healthcare systems are strained, addressing medical resource shortages is paramount. Focusing on healthcare infrastructure and access to vital medical services is vital to alleviate this strain on mental health.

- Employment status emerged as a decisive factor influencing household financial stability, and consequently, mental health. Our findings reinforce the urgency of initiatives aimed at creating job opportunities, reducing unemployment rates, and expanding the availability of unemployment insurance. Addressing employment-related challenges is integral to improving overall financial stability and promoting better mental health outcomes for individuals and families.


## 🐝 Part 4 Feature Engineering
<div align="center">
  
![](https://github.com/coconita526/capstone/blob/main/feature%20engineering%201.png)

</div>

- Relabel target columns from 2 classes into 3 classes
- Encoding columns with ordinal categories with ordinal numbers
- One-hot encoding for binary columns and create dummies for norminal columns.

## 💻 Part 5 Modeling & Evaluation 
<div align="center">
  
![](https://github.com/coconita526/capstone/blob/main/Model1.png)

</div>

- The best-performing model, based on accuracy rate, is still the Random Forest model after hyperparameter tuning (Model 6) with an accuracy rate of 71.67%.
- The decision tree baseline model (Model 9) initially had an accuracy rate of 61.06%, which is lower than other models.
- Decision trees are sensitive to the data they are trained on. The baseline decision tree might not capture the complexity of the relationship in the data well, resulting in lower accuracy.
- Hyperparameter tuning (Model 10) significantly improved the decision tree's performance, bringing its accuracy rate closer to other models at 70.39%.
- This improvement suggests that tuning the decision tree's parameters, such as depth and leaf nodes, allowed it to better capture the underlying patterns in the data, resulting in a more accurate model.

<div align="center">
  
![](https://github.com/coconita526/capstone/blob/main/model2.png)

</div>

- The top-performing model is XGBoost - Scaling & Hyperparameter (Model 8) with an accuracy rate of 70.59%.
    
- Baseline Decision Tree (Model 9):Default decision tree parameters may not suit the dataset, resulting in lower accuracy.
- XGBoost Strengths (Model 8):
    - Ensemble learning, handles non-linear relationships well.
    - Less prone to overfitting, benefits from scaling and hyperparameter tuning.
    - Regularization techniques and robustness contribute to its strength.


## 🌻 Part 6 Deployment 

<div align="center">
  
![](https://github.com/coconita526/capstone/blob/main/Deployment.png)

</div>

