# DiseasePredictingProject
This project predicts diseases suffered by a person based on the symptoms faced by them. The main objective of this model is to get an input from the user(symptoms) and display the disease to the user. This process involves the use of various Machine Learning algorithms and methods in implementing it. The main algorithm used as the base of this model is the SupportVectorMachine(SVM) and the classifier used for classifying the symptoms and diseases is known as SupportVectorClassifier(SVC).
The need for using SVM
SVM is a very powerfull algorithm when it comes to predicting models which is well known for giving the best accuracy. Other algorithms include DecisonTrees, RandomTrees and K-means regressors and classfiers. Upon testing all the above methods, SVM gave the most precise results with a higher accuracy.
Other ML mechanisms and processes involved are:-
1) Importing the necessary libraries.
2) Data preprocessing.
   1) Importing the dataset from the csv files.
   2) Transforming any strings present in the dataset to integers.
   3) Splitting the dataset into respective trainingset and testset in the ratio of 4:1.
   4) Applying feature scaling to avoid large deviation and variation in data.
3) Training the dataset using the SVM algorithm.
4) Predicting and displaying the respective disease to the user and checking its accuracy with preloaded dataset.

Tools and Softwares used:-
SKlearn 
Numpy
matplotlib
python
pandas
CSV files for dataset
PyCharm IDE
Tkinter for frontend
Any Backend software

Main Objective:-
Data(Symptoms suffered) given as input by the user in the tkinter GUI(frontend interface) will be stored in a backend interface from where it will be fed to the ML model which upon analysing the data will predict the output and display it back in the GUI.

Part of project accomplished:-
Trained the ML model to predict the appropriate disease to its best accuracy from the available dataset.

Pending part to be accomplished in teh future:-
Front-end user-friendly interface where the user can enter his/her input and an appropriate back-end interface to store the data processed by the model.
   
