# NTJ-Python_Model_Evaluation
:octocat: This repository introduces and summarizes common model evaluation indicators and methods.<br></br>
The notes contain the modules outlined below:<br>
|No.| Module| Gist|
|---|---|---|
|1|Overview|<li>1.1 What is Model Evaluation</li><li>1.2 Type of Model Evaluation</li><li>1.3 Over Fitting and Under Fitting</li><li>1.4 Model Generalization Ability</li>|
|2|**Classification Model**|<li>2.1 Confusion Matrix</li><li>2.2 Accuracy, Recall, Precision, etc.</li><li>2.3 F1 Score</li><li>2.4 AUC and its Index</li><li>2.5 PR Curve</li>|
|3|**Regression Model**|<li>3.1 Vector Distance</li><li>3.2 Mean Absolute Error (MAE)</li><li>3.3 Mean Square Error (MSE)</li><li>3.4 Root Mean Square Error (RMSE)</li><li>3.5 Explain Variation</li><li>3.6 Determination Coefficient</li>|
|4|**Clustering Model**|<li>4.1 Rand Index</li><li>4.2 Mutual Information</li><li>4.3 Profile Coefficient</li>|

## Overview
### 1.1 What's mdoel evaluation

## Classification Model
### 2.1 Confusion matrix
|predicted|actual|values|
|---|---|---|
|⬇️|➕|➖|
|➕|TP (1−β)|FP (α)<br>type I error|
|➖|FN (β)<br>type II error|TN (1−α)|
<li>A type I error corresponds to convicting an innocent defendant; misdiagnosis </li>
<li>A type II error corresponds to acquitting a criminal; missed diagnosis</li><br>

### Table of error types
In inferential statistics, the null hypothesis (often denoted  $H_0$)is that two (possibilities) are the same. <br>☝🏿 Hypothesis: "The patient has pneumonia."<br>👌🏿 Null hypothesis $H_0$ ✅: "The patient is healthy."
|error types| $H_0$ ✅| $H_0$❌|
|---|---|---|
|🙇🏻‍♀️|TN(1−α)|FN (β)<br>type II error|
|🙅‍♀️|FP (α)<br>type I error|TP (1−β)|
$H_0$ ✅ 
<li>😁 The people is healthy, but the physician judges the patient was ill. <br><li> 🙅‍♀️ A type I error is the mistaken rejection of a null hypothesis as the result of a test procedure.</li><br>

$H_0$ ❌
<li>🤧 The patient has symptoms of fever, cough, expectoration and chest pain, but the physician judges the patient was ok.<br><li>🙇🏻‍♀️ A type II error is the mistaken failure to reject the null hypothesis as the result of a test procedure.</li><br>

### 2.2 Accuracy, Recall, Precision
|term|formula| definition|
|---|---|---|
|accuracy|








