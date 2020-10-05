# Aim and Goals of the Project:
In this project, we will develop a trainer function to train a model with any training dataset, based on a multinomial version of Naive Bayes algorithm conditioned with additive smoothing. Trained model will be used for providing input to a binary classifier
- We will then unit test the trainer function to verify the accuracy of the complex calculations and code performed inside the trainer function.
- We will also develop a binary classifier or a filter function to distinguish between positive and negative based on trained model input (in this case spam and non-spam messages sent via SMS).
- Both the trainer and classifier will be general enough to be applied to a variety of problems requiring binary classification using any number of training datasets.
- We will also develop a third function aimed at determining the accuracy of the algorithm against a pre-classified test dataset
A human classified and labeled dataset, consisting of 5572 SMS messages will be used for calculation of prior probabilities (beliefs and evidences, as explained above) using the SMS training dataset. The binary classifier will then calculate the posterior probabilities for any new messages to be classified as spam or non-spam.
- Since any dataset of the format ['Label', 'Information'] can be used by the algorithm for training, We have also provided a A Guide for Data Cleaning and Formatting for use with the algorithm at Appendix-I
- Since a number of core probability functions are frequently required for basic calculations, We have developed a series of core conditional probability functions for use in any conditional probability problems These are enclosed as Appendix-II to this project.
