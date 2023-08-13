# Machine-Learning-Toolkit
Easy to use toolkit to do machine learning on any datasets (csv/excel). Will give interface to set up the ML model and data preprocessing. Can do choose a variety set of ML algorithms. There are three versions, one for binary classifcation problems, one for regression (continous numerical label) problems, and one for multi-label classifcation problems.

# IMPORTANT:
The dataset must be in the same directory as the code file. All features/varibles must be all ajacent to each other in a sequential row. The toolkit will ask for the feature both in the front and back end of that row.

Also note at some of the features in this toolkit may not work with some datasets depending on how it is structured. 
Also, some ML algorthims may work with some datasets depending on how it is structured.
Some models may take a long time to complete training and hyperparamter tune.

When the model is finished training and tested, it will produce the model, predictions, and probablites saved in .joblib files. It will also produce the cross valadtion results and accuracy in a textfile for the binary classifcation toolkit and the classifation report and accuracy in a textfile for the multi-label classifcation toolkit. For the binary classifcation toolkit, you will also get a .png file of the AUC Scores and the optional SHAP values if chosen.
