**WHAT IS LSTM?**
-LSTM is a special type of neural network which has a memory cell, this memory cell is being updated by 3 gates.
-Input gate: It just adds the information to the neural network
-Forget gate: It forgets the unnecessary data feed into the network
-Output gate: It going to get the desired answer out of the neural network.

![lstm](https://cdn-codespeedy.pressidium.com/wp-content/uploads/2019/11/0.png)

The input data is passed into the neural network and is updated for every input data

We normalize the data using [MinMaxScaler](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.MinMaxScaler.html)
Used Keras to build the stacked LSTM model

Stock price:
![og](https://github.com/aswinikalyan30/LGMVIP-DataScience_AswiniKalyan/blob/main/LSTM%20Stock%20Price/NiftyStock.jpg)

Predicted stock price:
![pred](https://github.com/aswinikalyan30/LGMVIP-DataScience_AswiniKalyan/blob/main/LSTM%20Stock%20Price/Prediction.jpg)
