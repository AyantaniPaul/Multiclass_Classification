# Multiclass_Classification

## **`Goal`**
This is a Liver Cirrhosis Stage Classification project. Several classification tools like Logistic Regression, Support Vector Classifier, Random Forrest Classifier and Histogram based Gradient Boosting Classifier are used to fit to the Liver Cirrhosis dataset which obtained from Kaggle. Then we compare the models and find out which model fits the data in the best way.

Source - https://www.kaggle.com/datasets/aadarshvelu/liver-cirrhosis-stage-classification/data

## **`Context`**
 Cirrhosis results from prolonged liver damage, leading to extensive scarring, often due to conditions like hepatitis or chronic alcohol consumption. The scar tissue prevents the liver working properly. Cirrhosis is sometimes called end-stage liver disease because it happens after other stages of damage from conditions that affect the liver. Two of the most well-known causes of liver cirrhosis are long-term excessive alcohol consumption and hepatitis C virus infection.. The data provided is sourced from a Mayo Clinic study on primary biliary cirrhosis (PBC) of the liver carried out from 1974 to 1984.

## **`About Dataset`**

- N_Days: Number of days between registration and the earlier of death, transplantation, or study analysis time in 1986
- Status: status of the patient C (censored), CL (censored due to liver tx), or D (death)
- Drug: type of drug D-penicillamine or placebo
- Age: age in days
- Sex: M (male) or F (female)
- Ascites: presence of ascites N (No) or Y (Yes)
- Hepatomegaly: presence of hepatomegaly N (No) or Y (Yes)
- Spiders: presence of spiders N (No) or Y (Yes)
- Edema: presence of edema N (no edema and no diuretic therapy for edema), S (edema present without diuretics, or edema resolved by diuretics), or Y (edema despite diuretic therapy)
- Bilirubin: serum bilirubin in [mg/dl]
- Cholesterol: serum cholesterol in [mg/dl]
- Albumin: albumin in [gm/dl]
- Copper: urine copper in [ug/day]
- Alk_Phos: alkaline phosphatase in [U/liter]
- SGOT: SGOT in [U/ml]
- Tryglicerides: triglicerides in [mg/dl]
- Platelets: platelets per cubic [ml/1000]
- Prothrombin: prothrombin time in seconds [s]
- Stage: histologic stage of disease ( 1, 2, or 3 ) 

### Citation:
Dickson,E., Grambsch,P., Fleming,T., Fisher,L., and Langworthy,A.. (2023). Cirrhosis Patient Survival Prediction. UCI Machine Learning Repository. https://doi.org/10.24432/C5R02G.

## **`Tools Used`**
1. Numpy
2. Pandas
3. Matplotlib
4. Seaborn
5. Scikit-learn
## **`What we will do:`**
1. Reading the data
2. Data Cleaning
   - Dealing with duplicates
   - Dealing with irrelevant columns
   - Dealing with outliers  
4. Exploratory Data Analysis
5. Data Preparation
   - Splitting the data into train and test data
   - Rescaling the data
6. Model building
7. Feature Importance
8. Model Evaluation and Comparison  
