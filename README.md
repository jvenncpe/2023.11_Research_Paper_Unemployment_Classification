<p align="center">
<img src="https://github.com/jvenncpe/2023.11_Research_Paper_Unemployment_Classification/assets/35190918/8f077445-50a7-4d8c-b9aa-2f2cebd62466"/></p>

# Research Paper: Unemployment Classification

Capstone project output from "Data Scientist Capstone Course" facilitated by Project SPARTA from Development Academy of the Philippines. The course aims to empower learners on the Data Scientist pathway to apply their analytics skills to real-world problems. Learners select local issues, using Philippine data to propose solutions, refining data collection, analysis, modeling, and presentation abilities. 

The course concludes with submissions detailing problem statements, objectives, analyses, results, conclusions, and recommendations, alongside detailed analysis materials. By the end, learners master problem conceptualization, data collection, analysis, interpretation, and decision-making insights.

## Overall Peer Grade Assessment

<p align="center">
<img src="https://github.com/jvenncpe/2023.11_Research_Paper_Unemployment_Classification/assets/35190918/48016a2f-98b2-4092-a7b8-95d87224e478")/></p>


## Activity

<p align="center">
<img src="https://github.com/jvenncpe/2023.11_Research_Paper_Unemployment_Classification/assets/35190918/94d70a0a-2fa8-4f40-86ad-2b7c76143018")/></p>


## Dataset Context

<p align="center">
<img src="https://github.com/jvenncpe/Unlocking-Opportunities-Unemployment/assets/35190918/e8a733b7-9d5d-41ef-954c-bfd4c78cb43b")/></p>

My main dataset was "LFS PUF January 2021" from the Philippine Statistics Authority (PSA) known as the Labor Force Survey (LFS) for January 2021. This dataset contains information about the labor force in the Philippines, including employment, unemployment, and other related indicators for that specific time frame.

Along with these are:

<p align="center">
<img src="https://github.com/jvenncpe/Unlocking-Opportunities-Unemployment/assets/35190918/51536803-4f6c-4776-98c6-cfa5fd48d320")/></p>


- lfs_january_2021_metadata(dictionary)
  - The metadata for "LFS January 2021" that includes information about the variables or attributes present in the dataset. It contain details about categories such as employment status, industry, occupation, education level, age groups, geographic regions, and various other factors related to the labor force survey conducted in January 2021 in the Philippines.

- phi-key-indicators-2023
  - This refer to a set of important statistical measures or indicators for the Philippines in the year 2023. These encompass various aspects such as economic, social, demographic, or other significant factors that provide a snapshot of the country's situation during that period. 

## Criteria

<p align="center">
<img src="https://github.com/jvenncpe/2023.11_Research_Paper_Unemployment_Classification/assets/35190918/e6375c64-ecfd-4e32-ba24-c225eb8662bf")/></p>


## Peer Grade Assessment Breakdown

<p align="center">
<img src="https://github.com/jvenncpe/2023.11_Research_Paper_Unemployment_Classification/assets/35190918/df81a67f-c156-49cc-ab84-ce9bf62b14e1")/>
<img src="https://github.com/jvenncpe/2023.11_Research_Paper_Unemployment_Classification/assets/35190918/912c3dbe-fb84-4cf9-accf-d8003cfe688d")/>
<img src="https://github.com/jvenncpe/2023.11_Research_Paper_Unemployment_Classification/assets/35190918/af9fb4b2-5114-4ade-b30f-ce29e2223215")/>
<img src="https://github.com/jvenncpe/2023.11_Research_Paper_Unemployment_Classification/assets/35190918/838ea808-fdb3-4788-81ec-f22ed30e077b")/>
<img src="https://github.com/jvenncpe/2023.11_Research_Paper_Unemployment_Classification/assets/35190918/83c5282f-f7df-4652-82b4-9050f3c03c75")/>
</p>

## Introduction and Background of the Project

<p align="center">
<img src="https://github.com/jvenncpe/2023.11_Research_Paper_Unemployment_Classification/assets/35190918/461a1978-9844-40cb-b0db-b13302036cbe" width="700"/></p>


## The Problem we're Tackling

<p align="center">
  <img src="https://github.com/jvenncpe/2023.11_Research_Paper_Unemployment_Classification/assets/35190918/471adf0d-7ab7-4fcd-b0ed-79a16aeb1db0" width="700" />
  <img src="https://github.com/jvenncpe/2023.11_Research_Paper_Unemployment_Classification/assets/35190918/409c7803-df59-479e-abbf-4d474460030a" width="700" />
</p>


## Implementation and Analysis

<p align="center">
<img src="https://github.com/jvenncpe/2023.11_Research_Paper_Unemployment_Classification/assets/35190918/74184f51-4f08-4b64-a33a-38a6ade06d1e"/></p>


### Data Exploration, Cleaning and Wrangling
The table headers and column inputs from the survey of “LFS PUF January 2021” are in special codes and are to be decoded based in "lfs_january_2021_metadata” as shown below:

> LFS PUF January 2021:

<p align="center">
<img src="https://github.com/jvenncpe/2023.11_Research_Paper_Unemployment_Classification/assets/35190918/ca14e9d8-d479-4ac3-8e2a-1cca6b3b2143"/></p>

>lfs_january_2021_metadata (column values):

<p align="center">
<img src="https://github.com/jvenncpe/2023.11_Research_Paper_Unemployment_Classification/assets/35190918/0848a261-cc2e-4430-8e4b-6f087547bc1c"/></p>

>lfs_january_2021_metadata (input values):

<p align="center">
<img src="https://github.com/jvenncpe/2023.11_Research_Paper_Unemployment_Classification/assets/35190918/6ea28ddc-a209-4bf6-b383-78860e8d8bdb")/></p>


The dataset was cleaned by removing columns that are not needed in the study and left with the table below:

<p align="center">
<img src="https://github.com/jvenncpe/2023.11_Research_Paper_Unemployment_Classification/assets/35190918/7c35c8b2-329a-4d60-8ee4-0013ae08f911")/></p>

The first column (naming code) from above are the column names from our “LFS PUF January 2021” and the “red” shaded cell is the assumed categorical classification to be used in our predictive analysis modeling as one of the solutions in the researcher’s statement of the problem.

Upon checking on “LFS PUF January 2021”, the columns are mostly filled with numbers however upon referring them into our metadata, they are accounted either an ordinal or categorical. This means most of the data inputs are qualitative as shown in the above table under “Type of Table”. Only “PUFC05_AGE” (C05-Age as of Last Birthday) and “PUFC33_WEEKS” (C33-Number of Weeks Spent in Looking for Work) are accounted as quantitative type.

The purpose of the column header “Available Data” is to determine if the column headers from “LFS PUF January 2021” has data count input in terms of “Employed” and “Unemployed” as shown below:

<p align="center">
<img src="https://github.com/jvenncpe/2023.11_Research_Paper_Unemployment_Classification/assets/35190918/846e1f77-4402-432f-886b-030c95211ca3")/></p>

The columns with no value count under “unemployed” or “employed” means that our dataset doesn’t contain participants that falls under that category. This also explains the limits from our scope and limitations.

In other words, it means that our dataset may not encompass the full spectrum of employment statuses, and certain categories, such as "unemployed" or "employed," might not be adequately represented due to the dataset's inherent constraints. This limitation should be taken into account when interpreting and drawing conclusions from the data analysis.

This also means that some of the columns may not be used depending on the requirements of the specific analytical technique to be used in the research.

### Descriptive Analytics

The researcher used descriptive analytics, including control chart and Pareto chart analysis, to gain insights and understand the challenges faced by unemployed Filipinos.

#### Control Chart Analysis

Using Control Chart Analysis, the researcher identified unusual employment rate patterns over time. Data from "phi-key-indicators-2023," including "Year," "Labor Force," and unemployment rate, was used for this analysis. To create the Control Chart, the researcher calculated the "Control Limit," "Lower Control Limit," and "Upper Control Limit."

<p align="center">
<img src="https://github.com/jvenncpe/2023.11_Research_Paper_Unemployment_Classification/assets/35190918/4114aa81-c470-4233-9645-b9ff0c5be0ba"/></p>

The table output (above) was produced by using the formula for UCL, CL & LCL as “Upper Control Limit”, “Control Limit” and “Lower Control Limit”, respectively.

The Center Line (CL) is calculated as the average or mean of the data points in the dataset. In this case, it represents the average unemployment rate over a certain time period, such as the years from 2005 to 2021.

The Lower Control Limit (LCL) and Upper Control Limit (UPCL) are calculated based on the standard deviation parameters of the dataset.
The CL at 7.00%, indicating the average unemployment rate, while the LCL and UPCL has values of 4.50% and 9.49%. If the unemployment rate falls between the LCL and UPCL, it is considered within control; if it falls outside these limits, it can be flagged as a significant deviation from the expected or normal range. These control limits help in identifying periods or years where the unemployment rate deviates from the expected range.

#### Pareto Chart Analysis

The Pareto Chart will identify and prioritize the most impactful factors contributing to unemployment, allowing us to focus on these critical. The advanced descriptive analytical tool was used to determine the primary occupations that are unemployed that needs assistance to find jobs with the aim of greatly reducing unemployment by 80% as shown below:

<p align="center">
<img src="https://github.com/jvenncpe/2023.11_Research_Paper_Unemployment_Classification/assets/35190918/2b5e1de7-2235-4cb0-9ff7-cfc4f473fd5e"/></p>

The table is from the "LFS PUF January 2021" dataset. It includes columns for primary occupations, the number of unemployed individuals in each occupation, the top priority occupations in need of assistance, the least priority occupations in need of assistance, and the cumulative percentage having a target of 80% of unemployment reduction.

To maximize the use of cumulative percentage, the table output was arranged in decreasing order based on the number of unemployed persons per primary occupation. As a result, when we reach the 80% target, primary occupations with a cumulative percentage below 80% (starting from the top) will be considered top priority, while the rest will fall into the least priority category.

### Diagnostic Analytics
#### Chi-square Test of Independence

The Chi-square Test of Independence is a statistical test used to determine if there is a significant association or relationship between two categorical variables. This advanced diagnostic analytic technique was used to determine the strength of association from employment status to region demographic profile, highest grade completed and technical/vocation graduate columns from the dataset "LFS PUF January 2021" having the pivot and association table shown below:

<p align="center">
<img src="https://github.com/jvenncpe/2023.11_Research_Paper_Unemployment_Classification/assets/35190918/5665e389-787c-4ae3-92cf-825a50ce7559"/>
<img src="https://github.com/jvenncpe/2023.11_Research_Paper_Unemployment_Classification/assets/35190918/025fd92c-506d-4540-a8e1-d7656a639ca1"/>
<img src="https://github.com/jvenncpe/2023.11_Research_Paper_Unemployment_Classification/assets/35190918/0eb6c2e3-e5f2-40e0-8a2c-b46a3de4b492"/>
<img src="https://github.com/jvenncpe/2023.11_Research_Paper_Unemployment_Classification/assets/35190918/1f8a4c2a-7b28-492a-9931-bf1827df97a5"/>
</p>

To create the association table for this test, the researcher referred to pivot tables, which provided a breakdown of percentage counts across "employed," "unemployed," and "not in the labor force" in relation to "region demographic profile," "highest grade completed," and "technical/vocational graduate."

The researcher then redistributed these percentage counts to construct an association table aimed at understanding the connections between these variables.

The researcher then assessed the strength of the relationship by using the Chi-square Test of Independence, which offers a P-value and its corresponding level of significance. 

This information can help in making a decision regarding whether to accept or reject the null hypothesis, in which suggests no significant association or relationship between the categorical variables under investigation as shown below:

<p align="center">
<img src="https://github.com/jvenncpe/2023.11_Research_Paper_Unemployment_Classification/assets/35190918/89dfe80c-8485-404b-a210-2b39d88afce8"/></p>

The outputs (p-value) were generated using the Excel data analysis function as shown below:

<p align="center">
<img src="https://github.com/jvenncpe/2023.11_Research_Paper_Unemployment_Classification/assets/35190918/c7609823-3499-4506-84b3-c1b89f6c666d"/></p>

#### One Way Analysis of Variation (ANOVA)

The One-way ANOVA will assess the impact of factors affecting different groups approach job searching.  The dataset was taken from "LFS PUF January 2021" having the overall age group table below:

<p align="center">
<img src="https://github.com/jvenncpe/2023.11_Research_Paper_Unemployment_Classification/assets/35190918/b1c339d5-2234-4587-9063-b54aaef13d47"/></p>

Please note that the table was for presentation purpose only and the input data that was used for the “One-way ANOVA” is the cleaned data wherein the age was not grouped yet. Knowing this, the output of the ANOVA is shown below:

<p align="center">
<img src="https://github.com/jvenncpe/2023.11_Research_Paper_Unemployment_Classification/assets/35190918/b7d1682d-76c8-4fb8-9d68-485372f73dbd"/></p>

The output was taken by using excel data analysis function. 

<p align="center">
<img src="https://github.com/jvenncpe/2023.11_Research_Paper_Unemployment_Classification/assets/35190918/d9a45db2-0d9e-4f0e-85e2-e5ca856cc119"/></p>

### Predictive Analytics
#### Logistic Regression

Logistic regression analysis is a statistical method used to model and analyze the relationship between a binary dependent variable (one that has only two possible outcomes, often coded as 0 and 1) and one or more independent variables (predictors or features). The primary goal of logistic regression is to predict the probability of the binary outcome – in our case, whether a person will find employment or not.

However, Logistic Regression was used in Jupyter Notebook rather than Excel in which needed to align with machine learning standards.

The researcher conducted additional comprehensive cleaning and filtering on the dataset "LFS PUF January 2021" to identify usable column features. This was done to reduce the amount of code needed in Jupyter Notebook. The resulting cleaned and filtered dataset was exported as "v0_SPCapstone002 Capstone – Predictive.csv" and will be imported for use in Jupyter Notebook, as demonstrated below:

<p align="center">
<img src="https://github.com/jvenncpe/2023.11_Research_Paper_Unemployment_Classification/assets/35190918/0a3bf862-714c-4500-9671-246ccb10eed5"/></p>

After importing of data, exploratory analysis was conducted to gain a deeper understanding of the dataset and its underlying characteristics, including dimensional assessment, scrutiny of null values, assessment of column data types, class distribution on binary output and evaluation of column names. This process provided a comprehensive foundation for subsequent data analysis, ensuring data completeness and reliability for advanced statistical and machine learning techniques.

<p align="center">
<img src="https://github.com/jvenncpe/2023.11_Research_Paper_Unemployment_Classification/assets/35190918/a35477aa-597e-4203-932a-7fa758f4d562"/></p>


One-hot encoding allows us to represent categorical variables in a way that machine learning algorithms can understand and process effectively. The researcher applied one-hot encoding to the columns 'PUFC06_MSTAT' and 'PUFC07_GRADE' because each of these columns contains two (2) distinct features. This step was taken to prepare the data for machine learning analysis, where these encoded features will play a crucial role in our predictive model.

<p align="center">
<img src="https://github.com/jvenncpe/2023.11_Research_Paper_Unemployment_Classification/assets/35190918/8ec72a9d-9f99-4478-9a6b-ed3fa8ae4a25"/></p>

In this phase, label encoding was applied to columns with more than two (2) features. The purpose of label encoding is to enhance the machine learning process by transforming categorical data into a numerical format, making it more amenable to algorithmic calculations and predictions. This preparation step plays a crucial role in ensuring that the dataset is compatible with machine learning models, ultimately improving the accuracy and effectiveness of the analysis.

<p align="center">
<img src="https://github.com/jvenncpe/2023.11_Research_Paper_Unemployment_Classification/assets/35190918/1d429e6c-3cc7-40e3-beb6-7307892937a5"/></p>


The researcher split the data in advance in order to have data exclusivity. This will allow us to have clearer data processing across the training and testing datasets and increase our level of caution during further preprocessing.

<p align="center">
<img src="https://github.com/jvenncpe/2023.11_Research_Paper_Unemployment_Classification/assets/35190918/e7510121-67ee-46cf-b683-7c0942dc1f09"/>
<img src="https://github.com/jvenncpe/2023.11_Research_Paper_Unemployment_Classification/assets/35190918/c4c2a5c1-04a2-4bdc-b357-494a6d5fb750"/>
</p>

Since during exploratory analysis, the class distribution was discovered to have output binary imbalance. The researcher proceeded to preprocess the dataset through SMOTE to create synthetic data inputs and mitigate class imbalance issue and ensure that the analysis remains robust as shown below:

<p align="center">
<img src="https://github.com/jvenncpe/2023.11_Research_Paper_Unemployment_Classification/assets/35190918/c013ca34-ce7d-487b-9b5e-ae8ac549f326"/>
<img src="https://github.com/jvenncpe/2023.11_Research_Paper_Unemployment_Classification/assets/35190918/e21e8cea-ae85-4ca7-8dd8-d7d98c0711e8"/></p>

However, the researcher needs to exercise caution when using SMOTE, as it has the potential to introduce data noise and may lead to overfitting, making it challenging for models to generalize effectively to unseen data. Overfit models often perform poorly in real-world applications. 

To address this concern, the researcher needs to conduct comparison between (1) SMOTE-processed 'X and y' training datasets and (2) 'X and y' training datasets before it was SMOTE-processed against the 'X and y' test dataset.

Hyperparameter Tuning was then carried out to find the best set of hyperparameters for a machine learning model, aiming to achieve optimal performance. This process involves a systematic search through a range of hyperparameter values and an evaluation of the model's performance for each combination as shown below:

<p align="center">
<img src="https://github.com/jvenncpe/2023.11_Research_Paper_Unemployment_Classification/assets/35190918/7ba9679f-7b0b-40f7-b434-4860f4024a6c"/>
<img src="https://github.com/jvenncpe/2023.11_Research_Paper_Unemployment_Classification/assets/35190918/123a2d53-e293-4350-abff-5904d6c37c38"/>
<img src="https://github.com/jvenncpe/2023.11_Research_Paper_Unemployment_Classification/assets/35190918/24213f18-ac65-494f-a944-ec67ea3978de"/>
<img src="https://github.com/jvenncpe/2023.11_Research_Paper_Unemployment_Classification/assets/35190918/bd2c2c07-c9dd-47eb-b403-89cea5be6d3c"/></p>

Two rounds of hyperparameter tuning were conducted to optimize the parameters for both the SMOTE-processed training dataset and the SMOTE-unprocessed training dataset. After hyperparameter tuning, the next steps involved model selection and training.

The researcher opted to use Logistic Regression for the model, with specific hyperparameters. For Logistic Regression A, which used the SMOTE-processed training dataset, the chosen hyperparameters were {“C” = 100, “solver” = "lbfgs"}. On the other hand, Logistic Regression B, utilizing the SMOTE-unprocessed training dataset, was configured with hyperparameters {“C” = 0.001, “solver” = "newton-cg"}. These hyperparameter choices were based on the results from the tuning process, as they achieved the best scores of 0.68 and 0.50, respectively.

<p align="center">
<img src="https://github.com/jvenncpe/2023.11_Research_Paper_Unemployment_Classification/assets/35190918/c8ea0f7f-c0c4-45f7-9363-0457bc3a8f18"/>
<img src="https://github.com/jvenncpe/2023.11_Research_Paper_Unemployment_Classification/assets/35190918/7a916a0c-bf12-4b94-9131-a0a838bfc31b"/>
<img src="https://github.com/jvenncpe/2023.11_Research_Paper_Unemployment_Classification/assets/35190918/13d4e849-c9ed-43ca-9a17-63b8013b722e"/>
<img src="https://github.com/jvenncpe/2023.11_Research_Paper_Unemployment_Classification/assets/35190918/89cfdf16-4a67-4aec-a177-507bb14bec1d"/>
</p>

Surprisingly, the model fitted using the SMOTE-unprocessed training dataset performed remarkably well, achieving accuracy scores of 0.92 for both training and testing. In contrast, the model fitted using the SMOTE-processed training dataset exhibited lower performance, with accuracy scores of 0.68 for training and 0.71 for testing, respectively.

This striking contrast highlights the impact of applying SMOTE in our machine learning process. It suggests that while SMOTE can be a valuable tool for addressing class imbalance, its application doesn't always guarantee improved model performance. In some cases, as observed here, the original unbalanced dataset may provide more reliable results. This outcome emphasizes the importance of carefully considering the specific dataset and its characteristics when deciding whether to employ SMOTE in a machine learning project.

After fitting the models and obtaining the accuracy scores, the next step involved comprehensive Model Evaluation. This evaluation process aimed to provide a more holistic understanding of how well the models were performing.

One of the key metrics used for assessment was the Receiver Operating Characteristic Area Under the Curve (ROC-AUC). The ROC-AUC is a measure of a model's ability to distinguish between the positive and negative classes. It provides valuable insights into the model's overall discriminatory power, making it a crucial metric for binary classification tasks.

Additionally, accuracy and F-1 score were examined. Accuracy, as previously mentioned, indicates the proportion of correctly classified instances, serving as a general indicator of a model's overall correctness. On the other hand, the F-1 score combines precision and recall, offering a more balanced evaluation, especially when dealing with imbalanced datasets.

<p align="center">
<img src="https://github.com/jvenncpe/2023.11_Research_Paper_Unemployment_Classification/assets/35190918/9592101b-c701-4f21-9ea0-17592d4bcfde"/>
<img src="https://github.com/jvenncpe/2023.11_Research_Paper_Unemployment_Classification/assets/35190918/cade9c84-1a71-4659-9db0-132e7da0c51c"/>
<img src="https://github.com/jvenncpe/2023.11_Research_Paper_Unemployment_Classification/assets/35190918/f6bc3332-ed2d-4cc0-8dfc-40cfce3c4e04"/>
<img src="https://github.com/jvenncpe/2023.11_Research_Paper_Unemployment_Classification/assets/35190918/96ac7824-e9f7-4798-94b3-8f72dd83e039"/>
<img src="https://github.com/jvenncpe/2023.11_Research_Paper_Unemployment_Classification/assets/35190918/37d43db8-8ac5-4d26-8731-56d3ecf47201"/>
<img src="https://github.com/jvenncpe/2023.11_Research_Paper_Unemployment_Classification/assets/35190918/6fe296bb-7830-4159-b800-d94ec510a00c"/>
</p>

Overall, the comparison between Logistic Regression B, fitted with SMOTE-unprocessed training datasets, and Logistic Regression A, fitted with SMOTE-processed training datasets, reveals that Logistic Regression B outperformed Logistic Regression A in multiple key metrics.

Logistic Regression B achieved a higher ROC-AUC score of 0.69 compared to 0.68 for Logistic Regression A, indicating a better ability to distinguish between positive and negative classes. Moreover, Logistic Regression B demonstrated superior accuracy, scoring 0.92 compared to 0.71 for Logistic Regression A. The F1 Score, which balances precision and recall, was also substantially higher for Logistic Regression B, measuring 0.96 compared to 0.82 for Logistic Regression A.

As a result of these superior performance metrics, the researcher made the decision to deploy Logistic Regression B as the chosen model for predicting the likelihood of a person being employed. This selection was based on Logistic Regression B's stronger overall performance, emphasizing the significance of ROC-AUC score, accuracy, and F1 Score in the decision-making process.

<p align="center">
<img src="https://github.com/jvenncpe/2023.11_Research_Paper_Unemployment_Classification/assets/35190918/77d77940-ca5a-45de-8bdb-aabaa12244ba"/></p>

The coefficients presented above hold valuable information about the likelihood of certain outcomes based on the features listed on their left side. In logistic regression, these coefficients help us understand the impact of each feature on the probability of a particular event occurring.

For example, a positive coefficient indicates that an increase in the corresponding feature will raise the likelihood of the event happening, while a negative coefficient suggests that an increase in the feature will lower the likelihood. The magnitude of the coefficient also matters; a larger coefficient signifies a stronger influence on the outcome.


## What we Discovered ...

<p align="center">
<img src="https://github.com/jvenncpe/2023.11_Research_Paper_Unemployment_Classification/assets/35190918/a8f78e49-f6e0-4328-9194-d7d653350e77"/></p>

### FULL RESEARCH PAPER OUTPUT CAN BE CHECKED AT: 
### • [2.0 SPCapstone002_JDColaste (Presentation Paper)](https://drive.google.com/file/d/16Y7QJVHbvTHTK7skXG6nLJNi_ohwsY3C/view?usp=sharing)

### • [3.0 SPCapstone002_JDColaste (Presentation Deck)](https://drive.google.com/file/d/16SjmWOwBjW2Ju-ZTiBa2O278qzXC7SWt/view?usp=sharing)

---
---

<p align="center">
<img src="https://github.com/jvenncpe/Unlocking-Opportunities-Unemployment/assets/35190918/6f659acb-88d0-49b2-8bc5-c65b81bfde52"/></p>


