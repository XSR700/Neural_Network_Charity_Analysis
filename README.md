# Neural_Network_Charity_Analysis

## Overview of the analysis: Explain the purpose of this analysis.

Bek's company AlphabetSoup is a philanthropic organization that collects donations to help non-profit groups. Bek is tasked with predicting which groups are worth donating to and which are high-risk. This analysis involves a deep learning neural network using Python's Tenserflow library. The code will evaluate all input data and produce a clear decision-making result. 

## Results: Using bulleted lists and images to support your answers, address the following questions.

### Data Preprocessing
  What variable(s) are considered the target(s) for your model? IS_SUCCESSFUL—Was the money used effectively
  What variable(s) are considered to be the features for your model? Application Type, Affiliation, Income Ammount, Classification, and Asking Amount.
  What variable(s) are neither targets nor features, and should be removed from the input data? Special Considerations
### Compiling, Training, and Evaluating the Model
  How many neurons, layers, and activation functions did you select for your neural network model, and why? 3 layers with 8, 5, and 5 neurons respectively. Each layer had a relu, relu, and sigmoid functions respectively. This model presented the best accuracy score. 
  Were you able to achieve the target model performance? No, the best result from optimization 3 showed a 72.4% accuracy score.
  What steps did you take to try and increase model performance? Increased/decreased neurons, Changed last activation function to Sigmoid, and added an extra layer. I used a sigmoid function because values are normalized to a probability between 0 and 1, which is ideal for binary classification.
  

## Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.

AlphabetSoup is trying to predict which donations lead to more probability of success based on variables given in the data. These feature variables include Application Type, Asking Ammount, and Classification which affected the outcomes for our neural model significantly. After running three optimization attempts, we managed to achieve a 72.4% accuracy score.

For better results and potentially achieving the desired 75% accuracy score, we can design the model better. Based on the practices from the Tenserflow neural network simulation, I higher epoch count allows the network more opportunity to predict with better accuracy. After all, each epoch count is a predicting attempt. For example, if we are exploring to find the highest peak of a mountain, we want to walk as much as possible on this mountain to reach the peak. In this case, an Epoch is like a step taken to find and reach the peak of the mountain. The problem with this optimization is computing power. Our computer will be working harder and longer with more epoch iterations.  





