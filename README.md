# Time-Series-Prediction
Predicting the number of arrivals at hospital emergencies using Recurrent Neural Networks (and a Multi-Layer Perceptron for comparison) 

Each notebook implements one model. 
MLP: implements a Multi-Layer Perceptron.
All other notebooks implement Recurrent Neural Networks:
- GRU.ipynb : a Gated Recurrent Unit Neural Network.
- LSTM_with_Memory_between_Batches.ipynb: a Long Short Term Memory Neural Network whose memory is not flushed after each batch.
- Stacked_LSTM_with_Memory_between_Batches.ipynb : an LSTM with Memory between Batches with more than one layer. 
- LSTM_for_Regression_with_without_Window_Method.ipynb: a model where the prediction problem is viewed as a regression one.
- LSTM_with_Timesteps.ipynb: 
- LSTM_Multi_Step.ipynb: an LSTM prediting 7 days ahead instead of only one.


All notebooks follow approximatetely the same workflow. Models have been strteched over different notebooks for clarity.

Note: The data used being private it is not provided here.
