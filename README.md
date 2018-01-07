# MotorImageryML
Brain-computer interfaces (BCI) are systems that decipher an individual's intents by analyzing their brain signals. These systems have shown the potential to be a solution for improving independent mobility in paralyzed individuals. In a motor imagery based BCI, an individual imagines the movement of a body part. The system subsequently decodes this signal (usually EEG signals) and provides a class prediction. Thus, accurate motor imagery classification is a requisite for successful BCIs. 

In this project, a variety of machine learning algorithms are used to discern between motor imagery of left-hand and foot from EEG signals; these models are: LDA, Linear SVM, RBF-Kernel SVM, Artificial Neural Network, Decision Tree, Logistic Regression, Majority Vote, Random Forest and Logit Boost. Most previous work has relied on linear classifiers for class prediction. In this work, we examine the use of more complex models (including ensemble classifiers) to improve classification accuracies in the 2-class motor imagery BCI paradigm. An elaborate discussion regarding the results and findings of the project can be found in 'classification-2-class.pdf'.

The dataset used was one used in BCI Competition IV and details regarding it can be found here: http://www.bbci.de/competition/iii/desc_IVb.html

To run the MATLAB scripts, open run_evaluation and run it in MATLAB.