# MLClassProject

The project of this project has 4 parts:
(1) get_embedding_for_texts.ipynb
This file will take the initial input file, and extract embeddings from the textual features, which will be used later.

(2) main_file.ipynb
This file defines the MLP backbone, and the training and testing pipeline. After the embeddings for textual features are obtained (named "data2.pkl"), this file can be run to train and test the model.

(3) clustering.ipynb
The main_file.ipynb can save some representations which will be used for clustering. The representation files are named "layer1_rep.npy" and "layer2_rep.npy". Then clustering.ipynb can be used to find clusters in from the representations.

(4) word_importance.ipynb
This file can be used to analyze the word importance of the textual features.
