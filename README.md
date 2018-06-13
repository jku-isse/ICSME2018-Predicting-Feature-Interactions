# Predicting Higher Order Structural Feature Interactions in Variable Systems

## ICSME2018 Data Repository

This repository serves to provide the data of an empirical study published at [ICSME'2018](https://icsme2018.github.io/index.html).

Link to the paper: will be provided once it is published.

Here we describe the files that exist for each system in the study.

### Data Description

**Raw Data**
- allModules.txt - Lists all modules that exist in source code.
- modules.csv - Number of modules in source code, by order
- inVM.csv - Number of modules in variability models, by order
- max.csv - Number of maximal possible modules without variability models, by order

**Raw Results**
- TP.csv - True Positive for prediction per order
- TN.csv - True Negative for prediction per order
- TN_max.csv - True Negative for prediction per order, without variability model restrictions
- FP.csv - False Positive for prediction per order
- FP_max.csv - False Positive for prediction per order, without variability model restrictions
- FN.csv - False Negative for prediction per order

**Metrics Results**
- prevalence.csv - Prevalence of modules in source code, in relation to modules in variabililty model, by order
- sensitivity.csv - Sensitivity of the prediction, by order
- specificity.csv - Specificity of the prediction, by order
- ppv.csv - Positive Predictive Value of the prediction, by order
- npv.csv - Negative Predictive Value of the prediction, by order
- accuracy.csv - Accuracy of the prediction, by order
- reduction.csv - Reduction of modules with the prediction compared to the variabiliy model, by order
- tpSubCount.csv - Number of times modules in TP have been predicted 
- fpSubCount.csv - Number of times modules in FP have been predicted 
- tpSubCountPerOrder.csv - Number of times modules in TP have been predicted, by order
- fpSubCountPerOrder.csv - Number of times modules in FP have been predicted, by order

**Metrics Results when applying a threshold of 2 for predictions**
- sensitivityFiltered.csv - Sensitivity of the prediction, by order
- specificityFiltered.csv - Specificity of the prediction, by order
- ppvFiltered.csv - Positive Predictive Value of the prediction, by order
- npvFiltered.csv - Negative Predictive Value of the prediction, by order
- accuracyFiltered.csv - Accuracy of the prediction, by order
- reductionFiltered.csv - Reduction of modules with the prediction compared to the variabiliy model, by order


