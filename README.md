# Dogs-VS-Cats
This is a Deep Learning Model to classify dogs and cats using CNN by Tensorflow and Keras.

## Data
The Link of dataset on Kaggle: [Dogs vs. Cats](https://www.kaggle.com/c/dogs-vs-cats).

The kernal on Kaggle: [Dogs VS Cats Binary Classification using CNN 93%](https://www.kaggle.com/abdelrahmanzied/dogs-vs-cats-binary-classification-using-cnn-93).




## Prerequisites
1. You should have python on your computer.
2. Install libraries:

    `pip install numpy`

    `pip install pandas`
    
    `pip install matplotlib`
    
    `pip install seaborn`

    `pip install warnings`
    
    `pip install scikit-learn`
    
    `pip install tensorlfow`
    
    
    If You want to install tensorflow GPU version you can check my article on Midium:

    [Install Tensorflow and Keras on GPU on Windows in 2021 using CUDA and cuDNN — All Errors are Fixed](https://abdelrahmanzied.medium.com/install-tensorflow-and-keras-on-gpu-on-windows-in-2021-using-cuda-and-cudnn-all-error-fixed-8a3967398eb7).

    If you have all prerequisites of tensorflow-gpu, just install using this command:

    `pip install --upgrade tensorflow-gpu==2.4.1`




## Usage
You can download the model "best_model.hdf5" file from [Kaggle](https://www.kaggle.com/abdelrahmanzied/dogs-vs-cats-binary-classification-using-cnn-93) notebook and import it using Tensorflow.

`Best_Model = tf.keras.models.load_model('best_model.hdf5')`


## Enjoy!
