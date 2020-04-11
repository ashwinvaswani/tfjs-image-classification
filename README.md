# Tfjs image classification

## Upload and classify images in browser using TensorFlow.js

**Tools used**: Keras, TensorFlow.js, Javascript, HTML

Steps to run : Open a new terminal, Go to the required directory and enter the following command <br />
```console 
python3 -m http.server 8001
```
**Note** : Here 8001 is the port number.You can choose any available port number of your choice.  <br /> 
Now, open a browser and open the link provided in the terminal window!

## Overview of project:
1. Create a keras model for a task ( image classification in this case )
2. Convert keras model to tfjs.layers format using the following code which gives a model.json file as output : 
```console
tensorflowjs_converter --input_format keras \
                       path_to_keras_model.h5 \
                       path/to/tfjs_target_dir
  
```
3. Create a simple HTML application and load model, images in it and make predictions using tensorflow.js.

## Sample output video :

![alt text](https://github.com/ashwinvaswani/tfjs-image-classification/blob/master/assets/output.gif)

