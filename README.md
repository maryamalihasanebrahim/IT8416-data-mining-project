# Detecting diabetes in Pima Indian females via supervised learning models

## Date: 03/06/2026

[YouTube Video Explanation](https://youtu.be/0BvPneSc8Hk) 

### By: 
202305541 Maryam Ali Redha\
202300786 Zainab Ali Almoalem\
202306578 Zainab Khalaf\
202300327 Nada Bader\
202301936 Abdulaziz Shawqi 


## **Description**
Lifestyle interventions are the most effective and powerful tools for controlling Type-2 diabetes and preventing excess complications in Type-1 according to the WHO (Diabetes, 2024). The motivation behind this exploration is to predict the possibility of diabetes within Pima Indians before life-altering symptoms begin to appear allowing individuals to make actionable lifestyle changes. 

The modelling part will be executed on AI Studio (previously RapidMiner Studio) exclusively. 

## **Individual model performances**
| Model | Accuracy | Recall	| Precision |
| -------- | -------- | -------- | -------- |
| Random Forest	| 77.63%	| 41.51%	| 88.00% |
| Naïve Bayes	| 81.58%	| 64.15%	| 79.07% |
| Generalized Linear Model	| 83.55%	| 71.70%	| 79.17% |
| Logistic Regression	| 83.55%	| 71.70%	| 79.17% |
| Gradient Boosted Trees	| 78.95%	| 71.70%	| 69.09% |

## **Ensemble model performances**
| Model	| Accuracy	| Recall	| Precision |
| -------- | -------- | -------- | -------- |
| Bagging |	79.61%	| 56.60%	| 78.95% | 
| Stacking	| 83.55%	| 71.70% |	79.17% |
| Boosting	| 83.55%	| 71.70%	| 79.17% |
| Vote | 80.92% |	62.26%	| 78.57% |

## **Results and inferences**
Logistic regression and ensemble model (stacking and boosting) resulted in a 83.55% accuracy which is higher than Naïve bayes model with 81.58% accuracy. For healthcare providers, logistic regression could be the most effective as it provides excellent data interpretation and pointing top performance which help them assess patient probabilities based on risk factors. Applying this model could improve the early diagnosis of high-risk women with the future inclusion of more dimensions due to critically absent attributes. The current models should not be used as the only basis of diagnosis without medical intervention. The addition of enough data attributes related to patient lifestyle and routine will aid healthcare providers in protecting patients with proper lifestyle changes before any symptoms appear. Direct correlations between the attributes at hand and the outcome (diabetic or not) are not strong enough to deduce causation from.

## **Recommendations**
For future implementation of the model and to diagnose patients with higher risk for diabetes we recommend to further improve the dataset attributes. During the project it was noticed that the limited dataset attributes or the factors used to predict patients were not enough resulting in low accuracy and higher recall rates, it might need more essential medical tests and patient lifestyle data as part of the improvement for higher accuracy percentage and efficient patient diagnosis. Currently the model performance cannot be used to give medical advice.


