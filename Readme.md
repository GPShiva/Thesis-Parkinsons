# Thesis-Parkinsons
# USING MACHINE LEARNING TO DIAGNOSE THE PATIENTS AFFECTED BY PARKINSON’S DISEASE

### Video submission link (https://youtu.be/89sZE8fLEgM)

## INTRODUCTION & PROBLEM STATEMENT 
• Parkinson’s disease (PD) is a progressive neurodegenerative disorder that affects more number of people around the globe everyday. 
• Patients diagnosed with PD have wide-ranging clinical characteristics, including motor and non-motor symptoms. Movement disorders including stiffness, resting tremor are some of the motor symptoms like Hallucinations, cognitive impairment, and impulse control disorders are some of non-motor symptoms. 
• There will be a near doubling of the number of elderly Europeans and North Americans affected by PD by the year 2050. While prevalence rates were generally lower in Asia than elsewhere, this also made PD a critical concern in Asia, where half of the global ageing population. 
• The precise cause of PD is still unknown, but various studies have shown that both genetic and environmental factors are involved
• It is essential to diagnose PD as early as possible to serve the general public in a cost-effective manner through latest techniques such as machine learning algorithms

## AIM AND OBJECTIVE
• The primary aim of this study is to provide an improved algorithm based on machine learning techniques that aidsclinicians in accurately diagnosing patients by that can distinguish between Parkinson's patients and healthy people. 
• To treat missing and duplicate values accordingly. For this study, there are no missing or duplicate values. 
• To bring numerical columns with various range to same range between 0 to 1 by using MinMax scalar which doesn’taffect the distribution of data. 
• To understand and estimate the performance of model in terms of Sensitivity, Specificity, F1 score and Accuracy. 
• Dealing with Imbalanced data by using ADASYN (Adaptive Synthetic Technique) to adaptively oversample minorityclass (class “0” or healthy) according to complexity of data.

## CONCLUSION & FUTURE RECOMMENDATION
• There are no missing values and duplicate entries. Most of the data is numerical data. Hence, no need to label encodethe data and it is easy for data pre-processing and model building. 
• Used MinMax scaling to bring range of all numerical data to one range which is 0 to 1 without affecting thedistribution of the data. ADASYN is used to tackle class imbalance
• Used various Classification machine learning algorithms and finally got an XGBoost algorithm on ADASYN datawhich gave highest sensitivity (0.98) and then highest specificity (0.87) which helps in predicting Parkinson’seffectively.

## FUTURE RECOMMENDATIONS
• The primary focus of future work should be on improving the performance of classification algorithms and also inusing various other approaches from feature selection methods in order to bring out improved results. 
• The current work only focused on the sensitivity of the model but the future work can also focus on improving theefficiency of model building both in terms of cost and time.
