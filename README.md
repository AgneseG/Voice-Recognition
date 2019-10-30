# Voice-Recognition

My model is based on the dataset **'Gender Recognition by Voice'** which consists of 3168 voice samples, half from females and half from males.

The original *.wave* files have previously been processed in R and are presented as a *.csv* file with 20 variables, which reflect the frequency parameters of the recorded voices.

The goal of my analysis is to build a model that will predict the gender based on the 20 frequency-related variables (__binary classification__).

To do so, I compared the performance of a logistic regression model to a random forest algorithm on the same variables.
