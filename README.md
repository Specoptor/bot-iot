**Objectives**

**Determine**
1. The appropriate transformations to preprocess the data as the input to a sparse autoencoder for anamoly detection, specifically for network intrusian detection in context of IOT.
2. The architecture of the autoencoder. 

**Deduce** 
1. the type of layers, number of layers, number of neurons and activation function of each layer, and number of dimensions in latent space. Determine the loss function, optimizer amongst other hyperparameters of model.
2. **Measure** sparsity between features, threshold, and weights.

**Compute** 
1. the reconstruction error, F1 score, False Alarm rate, accuracy, and recall. 

**Environment Setup**
1) Install Python 3.9 or higher
2) Set up virtual environment
    1. **Install** virtualenv `python -m pip install venv`
    2. **Create** virtual environment `python -m venv venv`
    3. **Activate** virtual environment 
       1. windows: `venv\Scripts\activate`
       2. linux: `source venv/bin/activate`
3) Install dependencies
    1) **Install** dependencies from requirements.txt 
       1) run `python -m pip install -r requirements.txt`
