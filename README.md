# AI_horse_prediction_2

*******************************

This is a continuation of the previous AI horse prediction project (https://github.com/StevenHo1394/AI_horse_prediction). Jupyter notebook is now used to facilitate performance valuation (by Tensorboard) and model refinement.

*******************************

This AI Horse racing prediction is using a N-layer Neural Network to predict the finishing position of each horse in a race. The data used to train this model is obtained from the Hong Kong Jockey Club (HKJC). The model is built and trained by Tensorflow 2.x. 

For the prediction results:

      Expected finishing positions= [ 4  2  2 11  6  4  9  9  4  1 12  5]
      
      The horse number "1" is expected to finish at position "4",
      The horse number "2" is expected to finish at position "2",
      ...
      The horse number "12" is expected to finish at position "5".
      
      So, we should bet on horses with expected finish positions = 1/2/3 on Win/Place/Quinella/Quinella Place/Trio; 
      and bet on "first four" or "Quartet" for horses with expected finish positions = 1/2/3/4.
      
Future planning: This is an ongoing project and the model and/or dataset will be updated from time to time. One possible way is to use reinforcement learning to bet on the results generated from the predictions and find out the bets that maximize the profits.

Disclaimer:
This model is regarded as an ongoing project of the author's interest and as a demonstration of deep learning usage. The author will not be responsible for any loss of investment that is caused directly/indirectly by this project.
