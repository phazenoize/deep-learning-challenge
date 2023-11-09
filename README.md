# deep-learning-challenge

What variable(s) are the target(s) for your model?

* The 'IS_SUCCESSFUL' column from application_df is the target variable, this is what we are trying to predict. This shows if the money was used effectively.

What variable(s) are the features for your model?
The feature variables we used are:
* AFFILIATION—Affiliated sector of industry
* CLASSIFICATION—Government organization classification
* USE_CASE—Use case for funding
* ORGANIZATION—Organization type
* STATUS—Active status
* INCOME_AMT—Income classification
* SPECIAL_CONSIDERATIONS—Special considerations for application
* ASK_AMT—Funding amount requested

What variable(s) should be removed from the input data because they are neither targets nor features?

* Identification columns: The "EIN" and "NAME" columns are identification columns that typically provide unique identifiers for each organization. These columns usually have no direct impact on the target variable and can be dropped without affecting the model's accuracy.

Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?

* I used 50 neurons in two hidden layers and one in the output layer. 

Were you able to achieve the target model performance?

* With 150 neurons and three hidden layers, the max accuracy held steadfast at 73.2% which is outside the goal of 75%.

![NN1](https://github.com/phazenoize/deep-learning-challenge/assets/10499935/e5c95889-9bab-4c1f-9399-aa8c7ceab62f)
![NN2](https://github.com/phazenoize/deep-learning-challenge/assets/10499935/6fc3f18c-78ed-4008-a5bc-d52fa813366a)

 
What steps did you take in your attempts to increase model performance?

* Adding more neurons didn't seem to truly help this model, changing the activation functions and adding more layers didn't seem to make too much of a difference either.

Summary:

* To improve the deep learning odel, the data should be re-cleaned with an added focus towards building a NN model by determining the specific takeaways being sought. This would help drive a more accurate outcome. The dataset is large, but having a larger dataset may help improve accuracy by adding sufficient complexity for the algorithm to work more intricately.
