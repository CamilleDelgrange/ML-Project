# ML-Project
> Project in machine learning, kaggle competition \n
> Introduction of the project: 
> In this project, we were given access to a database of responses from a subject who had been asked to rate the pleasantness of the smell of a large number of molecules; and a comprehensive list of the physical and chemical features of the molecules smelled. The ultimate goal of our algorithm is to predict the correspondence between the pleasantness of each smell and a given molecule. The data set and the task are derived from the paper : https://science.sciencemag.org/content/355/6327/820. You can find the complete project, documentation and dataset on our GitHub page: https://github.com/CamilleDelgrange/ML-Project 
<hr>

# <a name="team-members"></a>Team Members
* "Salomé Baup. Camille Delgrange" \n
https://github.com/salome-baup \n
https://github.com/CamilleDelgrange

# Variables:


# Precision:
> if the as.numeric() function doesn't work, please use the following code in the test set: (normally on jupyter lab, it is working)
> testset$Intensity<-gsub("low",2, testset$Intensity) 
> testset$Intensity<-gsub("high",1, testset$Intensity)
> testset$Intensity <- as.numeric(testset$Intensity)
> OR in the training set:
> data.predictors$Intensity<-gsub("low",2, testset$Intensity) 
> data.predictors$Intensity<-gsub("high",1, testset$Intensity)
> data.predictors$Intensity <- as.numeric(data.predictors$Intensity)


# How to reproduce the code ?
> You can find 2 files for the project, one "Project_Linear_Method.ipynb" where we put exploration of the data and the linear methods and a "Project_Non_Linear_Method.ipynb" containing the part with non-linear methods. You can execute them separately and get full reproducibility thanks to seed fixed. 
> You will need some librairies like : 
> Metrics, keras, caret, xgboost, tidymodels, leaps, randomForest, 

# Example of non-linear methods and associated presentation of results:
> randomForest:
> 

# R version:
 ![Capture.PNG](Capture.PNG) 

# Licence 
MIT licence
