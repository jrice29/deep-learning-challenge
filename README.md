# deep-learning-challenge
For this assingment, I used XPert Learning Assistance and Ask BCS Learning.

Data Preprocessing

What variable(s) are the target(s) for your model?
The target variable is the 'IS_SUCCESSFUL' column from application_df

What variable(s) are the features for your model?
The feature variables are every other column from application_df --> this was defined by dropping the 'IS_SUCCESSFUL' column from the original dataframe.

What variable(s) should be removed from the input data because they are neither targets nor features?
Both 'EIN' and 'NAME' columns were dropped/removed, because they were neither targets nor features for the dataset.

Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?
In the first attempt, i used 8 hidden_nodes_layer1 and 5 hidden_nodes_layer2. I decided to pick those two because I wanted to try which one would be best moving forward.

Were you able to achieve the target model performance?
I think I was partially able to achieve the target model performance.

What steps did you take in your attempts to increase model performance?
I incorporated additional layers, eliminated some columns, introduced extra hidden nodes, and adjusted the activation functions for each layer to try to enhance the model's accuracy.

Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.

Overall, the deep learning model achieved approximately 73% accuracy in predicting the classification problem. To improve prediction accuracy, a model with better alignment between input and output is needed. This can be accomplished by performing additional data cleaning beforehand, experimenting with different activation functions, and iterating the model until higher accuracy is achieved.
