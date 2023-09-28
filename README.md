## Sprin_12_Projects

# Rusty-Bargain-Car-Sale

# Project Description: 

Rusty Bargain used car sales service is developing an app to attract new customers. In that app, you can quickly find out the market value of your car. You have access to historical data: technical specifications, trim versions, and prices. You need to build the model to determine the value.

Rusty Bargain is interested in:

- the quality of the prediction
- the speed of the prediction
- the time required for training

# Project Instructions: 

1. Download and look at the data.

2. Train different models with various hyperparameters (You should make at least two different models, but more is better. Remember, various implementations of gradient boosting don't count as different models.) The main point of this step is to compare gradient boosting methods with random forest, decision tree, and linear regression.
   
3. Analyze the speed and quality of the models.
   
Notes:

- Use the RMSE metric to evaluate the models.
- Linear regression is not very good for hyperparameter tuning, but it is perfect for doing a sanity check of other methods. If gradient boosting performs worse than linear regression, something definitely went wrong.
- On your own, work with the LightGBM library and use its tools to build gradient boosting models.
- Ideally, your project should include linear regression for a sanity check, a tree-based algorithm with hyperparameter tuning (preferably, random forrest), LightGBM with hyperparameter tuning (try a couple of sets), and CatBoost and XGBoost with hyperparameter tuning (optional).
- Take note of the encoding of categorical features for simple algorithms. LightGBM and CatBoost have their implementation, but XGBoost requires OHE.
- You can use a special command to find the cell code runtime in Jupyter Notebook. Find that command.
- Since the training of a gradient boosting model can take a long time, change only a few model parameters.
- If Jupyter Notebook stops working, delete the excessive variables by using the del operator:
  del features_train

# Project Evaluation: 

- Have you followed all the steps of the instructions?
- How did you prepare the data?
- What models and hyperparameters have you considered?
- Have you managed to avoid code duplication?
- What are your findings?
- Have you kept to the project structure?
- Have you kept the code neat?

# Generated Plot: 
<img width="930" alt="image" src="https://github.com/nhayenquynh/Rusty-Bargain-Car-Sale/assets/125513684/0f8bfb94-fc6f-4c61-ada9-84563511ab6e">

# Result:
<img width="381" alt="image" src="https://github.com/nhayenquynh/Rusty-Bargain-Car-Sale/assets/125513684/51ecb80c-0cb3-4b65-98e3-72c62091fb64">

When trained with the train dataset, the CatBooster model performed the best in term of RMSE.

   
