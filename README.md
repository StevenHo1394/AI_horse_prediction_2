# AI_horse_prediction_2

*******************************

This is a continuation of the previous AI horse prediction project. Jupyter notebook is now used to facilitate performance valuation (by Tensorboard) and model refinement.

*******************************

This AI Horse racing prediction is using a 3-layer Neural Network to predict the finishing position of each horse in a race. The data used to train this model is obtained from the Hong Kong Jockey Club (HKJC). Please note that the author has no relation nor connection of any kind with the HKJC. The model is built and trained by Tensorflow. This project is 100% in Python.

Package: ./saved_model/*: pre-trained model using 50,000 epochs; horse_racing_model4.py: The NN model for horse racing; evaluate_model.py: To evaluate the performance of the model; predict3.py: Predict the results.

Usage: 1) make sure the pre-trained model is present. If not, train the model by running "horse_racing_model4.py"; 2) (optional) evaluate the model by running "evaluate_model.py" 3) (if new prediction needed) add a new csv, name as "horse_data_yyyymmdd_racex.csv" with the same format as the example "horse_data_20201202_race2.csv"; modify the line "dataset = pd.read_csv('horse_data_20201202_race2.csv')" to "horse_data_yyyymmdd_racex.csv"; 4) run the "predict3.py" and inspect the predicted results on console. For example, if we got this as the results:

      Expected finishing positions= [ 4  2  2 11  6  4  9  9  4  1 12  5]
      
      The horse number "1" is expected to finish at position "4",
      The horse number "2" is expected to finish at position "2",
      ...
      The horse number "12" is expected to finish at position "5".
      
      So, we should bet on horses with expected finish positions = 1/2/3 on Win/Place/Quinella/Quinella Place/Trio; 
      and bet on "first four" or "Quartet" for horses with expected finish positions = 1/2/3/4.
Future planning: This is an ongoing project and the model and/or dataset will be updated from time to time. (Latest upate on 2021/09/12 for new season 2021-2022)

Disclaimer:
This model is regarded as an ongoing project of the author's interest and as a demonstration of deep learning usage. The author will not be responsible for any loss of investment that is caused directly/indirectly by this project.
