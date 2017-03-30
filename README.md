# Artificial-Neural-Net-with-Python
This python program represents an ANN which can be trained with a test data and then tested with same/different set of data. Al the parameters required for training and testing are passed as parameters.

How to run the code:
1. Program has to be run in Eclipse IDE with python plugin added to it. Copy the files and import it in a new project in eclipse.
2. Used Numpy and Pandas packages. For this, download Anaconda software that includes all these packages and make the eclipse interpreter to point to the Anaconda python directory so that Eclipse can access both Numpy and Pandas packages as well.
3. Preprocessor.py file does preprocessing of the data into required format that Neural Net learner can recognize.
4. NeuralNet.py file will implement the Neural net algorithm and the arguments for both the files are implemented as mentioned below and this will take in the output file procduced by the preprocessor.py

<training data path> <testing data path> <error tolerance> <number of hidden layers - n> <number of nodes in hidden layer 1> <number of nodes in hidden layer 2> .... <number of nodes in hidden layer n>

