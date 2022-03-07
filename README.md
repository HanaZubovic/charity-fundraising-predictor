# Deep Learning Challenge: Charity Funding Predictor

Write a Report on the Neural Network Model

For this part of the Challenge, you’ll write a report on the performance of the deep learning model you created for AlphabetSoup.

The report should contain the following:

1. **Overview** of the analysis: Explain the purpose of this analysis.
The purpose of this analysis was to create a machine learning model that could accurately predict whehter a charity would obtain funding.
2. **Results**: Using bulleted lists and images to support your answers, address the following questions.
![Models](https://user-images.githubusercontent.com/16246354/157001972-692d5768-e4c8-4608-8758-102d5bf23744.png)

  * Data Preprocessing
    * What variable(s) are considered the target(s) for your model?
    * We are concerned with `IS_SUCCESSFUL` since it directly addresses whats being measured. 
    
    * What variable(s) are considered to be the features for your model?
    * Our featers were application type, classification, use case, organization, status, income amount, special considerations, and ask amount.
    
    * What variable(s) are neither targets nor features, and should be removed from the input data?
    * EIN and name were removed from the data since they arent relevant to our model. 
  * Compiling, Training, and Evaluating the Model
    * How many neurons, layers, and activation functions did you select for your neural network model, and why?
    * I used two neuron layers with RELU activations. The output layer leverages a sigmoid acctivation.
    *  Were you able to achieve the target model performance?
    *  The closest I got was roughly 72% accuracy. 
    *  ![Train_test](https://user-images.githubusercontent.com/16246354/157000291-8ebf289b-5d54-4ac0-9dbd-54b82d171af6.png)

    * What steps did you take to try and increase model performance?
    * I need to tweak with the layers and possibly add mor  epochs or different functions to see if I can increase that to 75%. 

3. **Summary**: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.
    * I wasn't able to reach the threshold of 75% yet, but with further adjustment its possible to manage. Thought it seems doubtful that it will go above 75% if only a couple of points. Its also a good idea to try other machine learning models to see if there is a better suited model. Perhave logistic regression. 
