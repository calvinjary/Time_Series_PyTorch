# Time_Series_PyTorch
Well commented, comprehensive and readable PyTorch code for time series based machine learning (in this case RNN, recurrent neural networks)

Features: 
    1. full parallel CPU and GPU support, dynamically chosen at the start of the code
    2. full batch training support, chosen as a hyperparameter by the user
    3. full support for training and testing loader, allowing chunks to be loaded and tested
    4. support for any number of features, as well as any prediction window size, and any sequence length


Comments about Variable names:
    "Train" means the data used for training (the ground truth, the data known and used to train the model). "Test" means the unknown data not used to train the model that we used to test the model's accuracy
    "X" implies the input data (meaning the feature information, the input data to the model) and "Y" implies the label (the ground truth, the value to the predicted, the output of the model)
    
In the context of the inner workings of the RNN/GRU/LSTM:
    X = input
    h = hidden
    o = output
    xh = input-to-hidden
    hh = hidden-to-hidden
    h0 = initial hidden state
    
    
