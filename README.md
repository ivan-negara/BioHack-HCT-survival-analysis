# BioHack-HCT-survival-analysis
## Motivation.

Graft versus host disease (GvHD) is a complication that might occur after an transplantation of bone marrow. GvHD is characerized by a high prevalence and probability of death. That is why the analysis of various factors impacting GvHD probability remains common problem in modern oncohematology. In the present project we propose to analyse a unique dataset containing data about GvHD diagnosis and treatment collected across 4 transplant centers in Russia. No statistical analysis of the data was done yet, so the team would make the first and important step in mining new insights in this field.

## Tasks

1. Cleaning and merging adequate datasets.
2. Getting known with the data and calculating descriptive statistics.
3. Conducting basic survival analysis, analyzing potential risk factors for survival and treatment response.
4. Building basic and advanced predictive models for survival and GvHD severity.

## List of files:
adagvhd.xlsx - collection of information regarding acute GvHD (collection from raw datasets together) 
adcgvhd.xlsx - collection of information regarding chronic GvHD (collected from raw datasets in one place). 
ADCM_A.xlsx - all information about acute GvHD therapy
ADCM_C.xlsx - all information about chronic GvHD therapy
ADCM_X.xlsx - all information about the therapy of 'cross' syndrome
ADSL.xlsx - data collected from all raw datasets to optimize table construction (one row per patient)
GVHD_FORM.xlsx - dataset containing all patients analyzed according to the protocol with available GvHD data
type_THSCA(1).xlsx - file for cumulative event rate with donor type. 
AGVHD_20230119_120304 - characteristics of acute GvHD
CGVHD_20230119_120304 - characteristics of chronic GvHD
CM_20230119_120304 - characteristics of treatment
DM_20230119_120304 - demographic data
GVHD_20230119_120304 - presence of aGvHD, supplemented by file view_THSC(1).xlsx 
PREV_20230119_120304 - prevention of GvHD
RS_20230119_120304 - refractoriness to steroid treatment.
STAT_20230119_120304 - overall survival and recurrence rates
TR_20230119_120304 - parameters of transplantation technology
TU_20230119_120304 - main diagnosis (indication for transplantation)  

## Methods

1. Descriptive statistics
2. Kaplan-Meier with and without landmark survival analysis and Cox ph-regression with time-dependent covariates, logit.
3. Decision tree for GvHD grading.
4. Gradient boosted survival analysis, random forest for survival analysis, basic ML-methods (logit, k-neighbor classifier etc) including stacking, hyper-parameter tuning with GridSearch.

## Key findings

1. OS and EFS is inferior among severe aGvHD patients when comparing to mild and absent cases.
2. Male gender, transplant type, MPN diagnosis are other potential risk factors for inferior OS and EFS.
3. ML-algorithms could be utilized in order to predict post-HCT survival and GvHD severity.

## Contributors
Oleg Arnaut, 
Ivan Negara, 
Alisa Selezneva, 
Nikita Volkov
