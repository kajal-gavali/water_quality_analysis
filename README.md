# Water Quality Analysis using Machine Learning Techniques

In this study, water quality was categorised into three categories 0, 1 and 2. Here, 0 means
water can be used for drinking, agriculture and industrial purposes.1 means water can be utilized
in agriculture and industrial usage. 3 means water can only be used within industries based on
industrial requirement but not suitable for drinking and agriculture usage. The six well-known
data mining classification methods listed below are used before defining final model for the
prediction of the same: KKneighbour, Decision Tree, Random Forest, LinearSVC, AdaBoost,
Stochastic Gradient Descent. The Overall Index of Pollution served as the foundation for each
classifier’s models. Temperature, turbidity, pH, and conductivity are the four water quality
indicators that were used to create the synthetic data set. These ranges met both domestic and
foreign standards. The DAS can be used to collect above parameters and given to ML model to
predict the quality of water. The parameters of each classifier were changed during the learning
phase to choose the ideal parameter values to learn a certain water quality class from the data
sets. During testing, each predictive model was verified using fictitious data and assessed using
parameters like accuracy, sensitivity, specificity, recall, and F1score. Random forest classifier
achieves the highest results out of the five different types of classifier.
