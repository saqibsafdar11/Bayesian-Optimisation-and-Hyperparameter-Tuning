# Datasheet for University Admission Dataset

## Motivation
The University Admission Dataset was created to train and evaluate machine learning models for predicting the probability of a student's admission to a university. This dataset aims to bridge the gap between traditional admission processes and data-driven approaches, potentially assisting students in making informed decisions and universities in streamlining their selection procedures.

## Composition
The dataset comprises instances representing individual student applications. Each instance contains the following features:

- GRE Score: Quantitative and Verbal Reasoning scores from the Graduate Record Examinations (GRE).
- TOEFL Score: Total score from the Test of English as a Foreign Language (TOEFL).
- University Rating: Numerical rating of the university the student is applying to (1-5).
- SOP Strength: Subjective rating of the strength of the student's Statement of Purpose (1-5).
- LOR Strength: Subjective rating of the strength of the student's Letter of Recommendation (1-5).
- CGPA: Cumulative Grade Point Average from the student's undergraduate studies.
- Research Experience: Binary variable indicating whether the student has research experience (1) or not (0).
- Admission Status: Binary variable indicating whether the student was admitted (1) or not (0).

## Collection Process
The data was collected from  UCLA Graduate University Admission Datasea. The data was then cleaned and preprocessed to ensure consistency and accuracy.

## Preprocessing/Cleaning/Labeling
The following preprocessing steps were performed:

- Missing values were imputed using appropriate methods based on the data type and distribution.
- Outliers were identified and handled using appropriate techniques.
- Categorical features were encoded using one-hot encoding or label encoding.
- The target variable, Admission Status, was labeled as 0 for non-admitted and 1 for admitted students.

## Uses
The UCLA Graduate University Admission Dataset can be used for various tasks, including:

- Training and evaluating machine learning models for predicting university admission.
- Analyzing factors influencing university admission decisions.
- Developing tools to assist students in choosing universities and preparing their applications.
- Conducting research on educational data mining and predictive modeling.

## Distribution
The dataset is available for download from [here](https://www.kaggle.com/datasets/akshaydattatraykhare/data-for-admission-in-the-university?resource=download).


## Maintenance
The dataset will be maintained by the research team responsible for its creation. Updates and improvements will be made periodically to ensure the dataset remains relevant and accurate.

## Additional Information
The dataset size and distribution of admission outcomes are not disclosed to protect the privacy of individuals and institutions involved.
The dataset may contain biases inherent in the data collection process and the universities represented.
Ethical considerations regarding data privacy and responsible use will be strictly adhered to.

This datasheet provides a comprehensive overview of the University Admission Dataset, its purpose, composition, and potential uses. It aims to promote transparency and responsible data utilization for advancing research and educational opportunities.
