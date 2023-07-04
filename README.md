# CS6375_assignment2: https://github.com/SparrowChang/CS6375_assignment2

All required files into a single ZIP archive: for submission.

0. 'README.MD'

1. 'nn_final.ipynb': 
    Colab https://colab.research.google.com/drive/1CzuFw9b8j7wnxmlzUt1d_oML2zaxlBOG?usp=sharing. Use Python 3.10.
    Dataset from UCI ML Repository and url='https://raw.githubusercontent.com/SparrowChang/CS6375_assignment1/main/auto%2Bmpg/auto-mpg.data. The train/test ratio 80/20. 
    Through Colab interface (with public read permission) -> Run all, it will evaluate training and test MSE under 3 activations (sigmoid, tanh, relu). For hyperparameters: epochs: [100, 500, 1000], learning rate: [0.001, 0.01, 0.1, 0.5]. Further generate 'path_to_log_file.txt', 'relu.png','sigmoid.png', 'tanh.png'. 

    - 'path_to_log_file.txt': 3 different activation (sigmoid, tanh, relu) combined with hyperparamters(learning rate and epochs), final we would get each activation the best parameter and its best MSE. There is without overfitting, the training error isn't significantly lower than the testing error. 
    
    - 'relu.png','sigmoid.png', 'tanh.png': each one is under same activation and best leraning rate, through the epochs train and test MSE plot.

2. 'CS6375 Assignment2_230704_final.pdf': report results in a tabular format with columns indicating the parameters for both train, test MSE for different combination of paramters and our conclusion is 






