# ML Earthquake Prediction #

Earthquakes disasters have been around in all our history, it would be great if we could the time ttf of an earthquake given 
the electromagnetic singal that emits long before its appearance. A good prediction would help us prevent and avoid a lot 
of damages. 
![Alt text](images/header.png?raw=true "Header")

## Model Architecture ##
Many models where tried but the model that obtained the best accuracy rate for the test set was a stacked ensemble with a blender, 
3 different models tried to make a prediction and a neural network (blender) was trained with the output of the stacked models. Each of the models in the first prediction layer was selected given their outstanding performance compared to others.  
![Alt text](images/earthquake.png?raw=true "Header")

## Prerequisites ##

    python>=3.7
    numpy>=1.16.2
    pandas>=0.24.1
    matplotlib>=3.0.2
    tensorflow-gpu>=2.0.0a0
    scipy>=1.1.0
    scikit-learn>=0.20.3
    

## Where can I get the dataset? ##

Unfortunately the original training and testing dataset is too big, thus it is not uploaded here.
Nevertheless, you can get it from https://www.kaggle.com/c/LANL-Earthquake-Prediction
