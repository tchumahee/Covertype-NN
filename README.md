# Covertype-NN
A simple neural network that predicts forests based on the Covertype dataset.

The dataset is unabalanced, which I corrected for by undersampling, so results are more accurate across all classes.  
A heatmap visualizer of the confusion matrix was added to show the results pre and post training.  
Early stop is implemented during training, with a patience of 3 epochs.
