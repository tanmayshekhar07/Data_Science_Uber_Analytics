# Data_Science_Uber_Analytics

*Abstract*

The goal was to construct a realistic model to precisely predict the price of an uber ride in Boston. 
It is generally believed that it’s impossible to precisely predict a fair price of a cab ride as it depends on various factors. 
For this dataset price is the dependent variable and others are independent variables. First, major factors affecting the cab fares 
should be selected. Then, a model for cab ride price prediction should be established from linear regression. 
That should be applied to the boston cab rides dataset to test the model. Through the data analysis and test it can be summarized 
that the linear regression model can effectively predict and analyze the cab ride price to some extent, while the algorithm can 
still be improved through more advanced machine learning methods.

The notebook aims to construct a realistic model to predict the price of an Uber ride in Boston. The primary goal is to challenge
the belief that it's impossible to precisely predict cab fare prices due to their dependency on various factors.

The approach involves:

* Identifying major factors (independent variables) that affect cab fares (the dependent variable).
* Establishing a prediction model based on linear regression.
* Applying this model to a dataset of Boston cab rides to test its effectiveness.
* Summarizing the results and exploring potential improvements through more advanced machine learning methods.


*Specific Methodological Steps*

* Data Preparation: There's a mention of addressing non-numeric values in the dataset. This likely involves converting 
non-numeric values to NaN and then dropping rows with NaN values to ensure the dataset is suitable for analysis.

* Data Splitting: The data is split into training and testing sets, which is a common practice in machine learning to evaluate the performance of models.
Model Analysis: SHAP (SHapley Additive exPlanations) analysis is conducted on a Random Forest model. This suggests an exploration of feature importance and impact on the model's predictions.

*Additional Notes*

The methodology focuses on linear regression but also mentions the possibility of exploring more advanced machine learning methods.
The notebook includes practical steps for data cleaning and preparation, essential for machine learning tasks.
This summary provides a general idea of the methodology used in the notebook. For a more detailed understanding, 
a thorough review of the entire notebook, including code cells, would be necessary. 
If you have specific sections or code blocks you'd like me to review, please let me know. ​​

*Author*

Tanmay Shekhar is the Author of this notebook. 
Tanmay is a Graduate Student at Northeastern University pursuing his masters in Information Systems and specializing in Data Analytics.

*Conclusion* 
Both SHAP and LIME are popular techniques used for interpreting the predictions of machine learning models,
but they differ in their strengths and limitations.
* SHAP is a global explanation method that assesses the importance of each feature across the entire dataset.
  It employs game theory and provides a consistent and rigorous approach to feature importance that is not influenced by
  the choice of background distribution. SHAP values have several desirable characteristics, including local accuracy,
  consistency, and missingness.

* LIME, on the other hand, is a local explanation method that generates a simplified model to approximate the behavior
  of the original model in the vicinity of a specific instance. It accomplishes this by perturbing the input features
  of the instance and observing the effects on the model's output. LIME is relatively straightforward to use and can
  be applied to a broad range of models.

* Each of these model interpretability techniques has its own unique set of applications and benefits, and
  their use should be determined based on the specific model analysis needs.



  ## MIT License

Copyright (c) 2023 Tanmay Vijay Shekhar

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), 
to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, 
distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
