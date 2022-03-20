# Neural_Network_Charity_Analysis

# Overview of the analysis: 

Beks has come a long way since her first day at that boot camp five years ago—and since learning about neural networks earlier this week! She's now ready to put her abilities to use by assisting the foundation in predicting where to spend. With my background in machine learning and neural networks, I'll utilise the attributes in the dataset to assist Beks in developing a binary classifier that can predict whether applications would be successful if they are financed by Alphabet Soup. Beks got a CSV comprising more than 34,000 groups that have received financing from Alphabet Soup throughout the years from Alphabet Soup's business team. 

# Results: 

## What variable(s) are considered the target(s) for your model?

The "IS SUCCESSFUL" column is used as the model's aim. 

## What variable(s) are considered to be the features for your model?

The below variables are considered to be the features of the optimized model:

-“APPLICATION_TYPE”

-“CLASSIFICATION”

-“AFFILIATION”

-“ORGANIZATION”

-“STATUS”

-“INCOME_AMT”

-“ASK_AMT”

## What variable(s) are neither targets nor features, and should be removed from the input data?

The below variables are neither targets nor features, and should be removed from the input data:

-"EIN"

-"NAME"

-"USE_CASE"

-"SPECIAL CONSIDERATIONS"

## How many neurons, layers, and activation functions did you select for your neural network model, and why?

For my neural network, I chose the following neurons, layers, and activation functions. 

Attempt 1 -2 Layers -90 and 45 neurons -Relu activation -40 epochs

Attempt 2 -3 Layers -50, 30, and 10 neurons -Relu activation -30 epochs

Attempt 3 -3 Layers -80, 20, and 30 neurons -Tanh activation -100 epochs

In order to boost the predicted accuracy to 75%, I chose each of them at random using the trial-and-error approach. Initially, I just raised the number of neurons to test whether a simple solution would result in a higher degree of prediction accuracy, but the problem was not simple enough to be linearly separated, as was thought.As a result, in each successive effort, I decided to increase the layers, nodes, and epochs, based on the principle of "going for depth," which claims that "Empirically, more depth does tend to result in better generalisation for a wide range of tasks." 

## Were you able to achieve the target model performance?

I was unable to meet the 75 percent model performance goal.

In hindsight, or possibly on a subsequent try, I would have raised the number of layers to incorporate greater depth, since this would allow the model to build more shapes and samples for categorization, improving predicted accuracy. 

## What steps did you take to try and increase model performance?

To improve the model's performance, I did the following steps:

For all subsequent model setups, remove any extra features (noisy variables).

Increase the number of layers

Increase or reduce the number of neurons in the extra layers

Each effort may be broken down into the following categories. 

Attempt 1 -2 Layers -90 and 45 neurons -Relu activation -40 epochs

Attempt 2 -3 Layers -50, 30, and 10 neurons -Relu activation -30 epochs

Attempt 3 -3 Layers -80, 20, and 30 neurons -Tanh activation -100 epochs

Below is a screenshots of the code used to increase model performance.

<img width="935" alt="image" src="https://user-images.githubusercontent.com/93067732/159151219-4b86290d-b7c9-4104-a16f-70cc68d39314.png">

<img width="932" alt="image" src="https://user-images.githubusercontent.com/93067732/159151250-729bd75c-2029-441e-b575-544f7246fea2.png">

<img width="1016" alt="image" src="https://user-images.githubusercontent.com/93067732/159151283-7720cf3d-4461-4607-aa2c-5136f6dbc2a5.png">

<img width="523" alt="image" src="https://user-images.githubusercontent.com/93067732/159151293-1a9375c1-e6d4-4ad6-bb6f-2dbfc9f86bbb.png">

<img width="873" alt="image" src="https://user-images.githubusercontent.com/93067732/159151300-d26a8efb-3608-483c-ab9f-952696698cb0.png">

<img width="970" alt="image" src="https://user-images.githubusercontent.com/93067732/159151311-2c9a377d-5342-4d85-b5d6-936101bb450e.png">

<img width="880" alt="image" src="https://user-images.githubusercontent.com/93067732/159151323-3bd4a57e-d3a1-4088-9716-4b3817cbc1b0.png">

<img width="875" alt="image" src="https://user-images.githubusercontent.com/93067732/159151331-9cd45d53-8b18-4776-acbf-37534a59e1c9.png">

<img width="902" alt="image" src="https://user-images.githubusercontent.com/93067732/159151350-11c582cc-030e-403c-b727-17303f732816.png">

<img width="919" alt="image" src="https://user-images.githubusercontent.com/93067732/159151357-bdb8df2c-7440-408c-80e0-2230f10fa54b.png">

<img width="751" alt="image" src="https://user-images.githubusercontent.com/93067732/159151387-f81ddf9c-36f3-439c-a8dc-95cfdbf80ab6.png">

<img width="541" alt="image" src="https://user-images.githubusercontent.com/93067732/159151411-2162a8c2-f35d-40f6-b80c-7611284d05b0.png">

## Summary:

Attempt 1: Predictive Accuracy Percentage: 72% Loss Metric: 56%

Attempt 2: Predictive Accuracy Percentage: 72% Loss Metric: 56%

Attempt 3: Predictive Accuracy Percentage: 72% Loss Metric: 57%

## Recommendation: 

While none of these models attained a predicted accuracy of 75%, I would propose increasing the amount of hidden layers to add more depth in the model to tackle the categorization problem in future tries. Increasing the depth (layers) of the model would allow for a greater creation of predictability shapes and patterns; increasing the layers by a large margin may create an upper bound, from which I could fine tune the model by varying the number of nodes, or by decreasing the number of layers from the upper bound, using a trial-and-error method, to achieve a predictive accuracy of 75%. 
