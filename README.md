# Forest Cover Classification Using Deep Learning

In this project, I will use deep learning to predict forest cover type (the most common kind of tree cover) based only on cartographic variables. The actual forest cover type for a given 30 x 30 meter cell was determined from US Forest Service (USFS) Region 2 Resource Information System data. The covertypes are the following:

* Spruce/Fir
* Lodgepole Pine
* Ponderosa Pine
* Cottonwood/Willow
* Aspen
* Douglas-fir
* Krummholz

Independent variables were then derived from data obtained from the US Geological Survey and USFS. It contains binary columns of data for qualitative independent variables such as wilderness areas and soil type.

This study area includes four wilderness areas located in the Roosevelt National Forest of northern Colorado. These areas represent forests with minimal human-caused disturbances, so existing forest cover types are mainly a result of ecological processes rather than forest management practices.

### Project Objectives:

* Develop one or more classifiers for this multi-class classification problem.
* Use TensorFlow with Keras to build the classifier(s).
* Hyperparameter tuning to improve performance. 
* Test & analyse performance. 
* Create clean and modular code. 

## Results

The model achieved a F1 score of 0.83. I think this could improved as the val_accuracy was still increasing as the number of epochs completed. 
