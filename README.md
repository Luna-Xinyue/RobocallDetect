# Robocall Detection

## How to run

### Prerequisite
- numpy
- pandas
- matplotlib
- sklearn
- pandas
- pickle
- imlearn

For running all the performance test, *DecisionTree.py* and *detect.py* is what you need. DecisionTree.py will give you information about how overall accuracy, precision, recall and F1-score the model's like. Since this task needs a binary classifier, detect.py focused on models‘ accuracy for each class, which is "Fruad" and "Normal" in this task. We have the completion that **desicion tree** is the best one for this task. 

Using *main.py* to generate models. It requires path to train data, portion (of split train and test data), and train epoch as parameters to train a model. Setting F1-score as standard to decide whether a model is better than other. Moreover, it will vectorize new data for prediction.

