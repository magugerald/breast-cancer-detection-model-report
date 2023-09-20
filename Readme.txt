Breast Cancer Detection Model Report
About the Model
The task involved the creation of a breast cancer detection model through the use of a Random Forest Classifier. 
Fundamentally, the model objective was to classify the diagnosed cells as either Malignant (cancerous) or Benign (not cancerous). 
Using a total of 30 features that were computed for each cell, 
the model was successfully able to classify each diagnosed cell with high accuracy.

Dataset: The dataset used in this model was provided by the lecturer on the institution’s website.  
The dataset had a total of 569 observations and 33 variables. 

Data preprocessing: The data contained only one column mostly filled with null values. 
To fix the null values, the column was dropped as it didn’t have much impact on the overall data. 
Also, and as part of data preparation, the variables that contained categorical values were replaced with numerical values. 
Lastly, the data was standardized to ensure no overfitting or underfitting of the model.

Visualization: Four main graphs were used in this model development to illustrate various operations. 
One, a heatmap was used to visualize the null values in the data. 
Secondly, a count plot was used to visualize the distribution of Malignant and Benign cells on the diagnosis column. 
Thirdly, a bar plot was used to display the correlation distribution between the diagnosis variable and the rest of the features. 
Lastly, the ROC curve was used to show the performance of the model.

Model, Prediction, and Results: After dividing the model into independent and dependent variables. 
The dataset was then split in the ratio of 0.7 and 0.3 for training and testing respectively.  
The Random Forest Classifier was then applied for training the model. 
After training and prediction, the model achieved an accuracy level of 0.96 or 96%. 
Other operations such as cross-validation, confusion matrix, and ROC curve were carried out as shown on the code.

Conclusion: After the successful development of the model, 
then I am certain that the model can help detect breast cancer with an accuracy of 96%.
