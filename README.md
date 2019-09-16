# What-makes-pokemon-legendary
This Jupyter Notebook runs through a classification/random forest prediction to discern what attributes make up a pokemon's legendary status

This project was written in R and uses packages: Tidyverse (which includes ggplot and Dplyr), Rpart, randomForest, and ROCR.

**Tidyverse** was used to display visualizations and manipulate the data, \n
**Rpart** was used to fit a decision tree \n
**randomForest** was used to fit a random forest, \n 
**ROCR** was used to create a prediction and performance plot for both the rpart object and random forest object as well as assess the importance of each of the variables using (MeanDecreaseAccuracy – how much the model accuracy suffers if you leave out a particular variable and MeanDecreaseGini - the degree to which a variable improves the probability of an observation being classified one way or another (i.e. 'node purity') 
