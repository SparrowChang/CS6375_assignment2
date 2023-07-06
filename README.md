# CS6375_assignment2: https://github.com/SparrowChang/CS6375_assignment2

In a ZIP archive. Here are the files and their descriptions:

0. README.md: This file contains any necessary instructions or information about the project.

1. nn_final.ipynb: 
    This Colab notebook can be accessed at https://colab.research.google.com/drive/1CzuFw9b8j7wnxmlzUt1d_oML2zaxlBOG?usp=sharing. 
    It is designed to be run with Python 3.10. The notebook uses a dataset from the UCI ML Repository, obtained from the URL: https://raw.githubusercontent.com/SparrowChang/CS6375_assignment1/main/auto%2Bmpg/auto-mpg.data. The training and test dataset is split with a ratio of 80:20. 
    Running all cells in the Colab interface will evaluate the training and test Mean Squared Error (MSE) using three different activation functions (sigmoid, tanh, relu).
    The notebook also explores different hyperparameters: epochs (100, 500, 1000) and learning rates (0.001, 0.01, 0.1, 0.5). The following files will be generated within the notebook:
        - path_to_log_file.txt: This file contains the best hyperparameters and corresponding MSE for each activation function.
        - relu.png, sigmoid.png, tanh.png: These files are plots of the training and test MSE for each activation function, using the best learning rate found.

2. CS6375 Assignment2_230705_final.pdf: This file is a report presenting the results in a tabular format. The table includes columns for the parameters used, as well as the train and test MSE for different combinations of parameters. The report also includes conclusions based on the results.


