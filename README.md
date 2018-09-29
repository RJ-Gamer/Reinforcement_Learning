# Reinforcement_Learning
Stock Prediction of google stock data using reinforcement learning

Here GSPC.csv is a trainging dataset
And GSPC_2011.csv is test data set

to run the program run the following commands:

// Locate to the directory where all files are saved 

  mkdir models
  python train.py 10 200 (take time around 2 to 3 hrs)

after finishing the training run the following :
  
    python evaluate.py GSPC_2011 model_ep0
    
