Brett's Medical Cost Dataset Review

Notebook: [regression_neely.ipynb](https://github.com/bncodes19/ml-regression-neely/blob/main/regression_neely.ipynb)

Date: 10 April 2025

1. Clarity & Organization (Is the notebook structured and easy to follow?)
 - Yes, this notebook is well structured and easy to follow.  It is well commented too.  
 - I would have preferred more visuals in this notebook.  The data exploration consisted of only four plots.  It is my opinion that more exploration of the dataset could have yielded additional insights into the dataset.

2. Feature Selection & Justification (Do the chosen features make sense given the objectives?)
 - Age, smoker and sex are good choices
  - I wonder if more time had been spent on data exploration if obesity/bmi would have been identified as an important variable.  BMI was included in the pipeline model though.  Also, could some features have been engineered?  Could age have been binned into categories?  Does BMI have accepted categories?  Ratio features such as BM/age?  Or combinations like obese and smoker? 

3. Model Performance & Comparisons (Are the results and comparisons clearly explained?)
 - The metrics are well laid out here and the comparisons are clearly explained.
 - Could more models have been included?  Tree based models?  Boosted models?

4. Reflection Quality (Are insights well thought out?)
 - Yes, the insight that the pipeline performed better was well explained.
 - I would have liked to have seen the engineered features that were propsed in the final thought applied to the model.
