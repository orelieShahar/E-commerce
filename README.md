# e-commerce
E-Commerce Course Final Project - Recommendation Systems 


This is the final project of e-commerce course that was deliver by Asi Messica at Ben-Gurion University. 

Please download the 100k movielens database, link and instructions for the project are attached.

The answers to the work are attached in 2 versions - Hebrew and English.

Good luck! :)



Download the dataset 100000 lens movie.
Link to dataset:  https://grouplens.org/datasets/movielens/100k/
•	Use the u1 file for train and test. 
•	Perform the analysis In the jupyter notebook, 
•	answer the answer in a jupyter notebook and word file. 
•	Use the same division for train and test In which you used Exercise Number 2 for comparison. (80% train 20%test)
•	The training is performed based on the train file and the file test The test.

 Exercise 1
A.	create Modeling a rating model for a movie (recommend system) for a user based on the standard factorization matrix model, as the explain presentation in the classroom (see jupyter notebook I send).
So need to create Mf model, and GMF model for rating predict for a movie for users.
B.	calculate the average MAE for the test group. 
Check the results for 2 options for the layer dimension embedding, and 2 option for drop out (total of 4 options for one of the models (mf/GMF), and one option for the second model). 
C.	Compare the results you received according to the different models(MF/GMF) and the results you received in exercise number 2 (need to create – a Non-personal recommendations system also on the same data and split train and test – predict according to the rating average of each movie) 
Which method worked better the non-personalized from hw2 or MF or GMF? 
Show the MAE results and duration of training for each model and explain.

Exercise 2
A.	create a model that used to predict the rating of a film for a user based on a model of collaborative neural filtering cnf model that was show in Classroom ( see notebook I send). 
Start from a model with one hidden layer. 
B.	calculate the average MAE for the test group.
 Check the results for different parameter options Of the cnf model: 
•	number of layers,
•	 size of each layer
•	 the optimizer
•	the function loss
•	the activation function of the intermediate layers. 
      Total Check 4 different options to choose from. 
C.	Compare the results you have received based on the different models (MF/ GMF / CNF). Which method worked better with what parameters? why? 
D.	Show the MAE results and duration of training for each model and explain.


Exercise 3 
A.	In addition to viewing data, the dataset contains additional data about films and viewers such as the film category, gender of Viewer, viewer age, occupation etc. Suggest a way to incorporate film characteristics (features) and / or user feature to the models you implemented.
In your proposal, consider and explain:
•	the choice of additional features – what and why
•	the model architecture 
•	data processing Required to enter the data into the model. 
B.	Select two properties (feature ) for a movie and / or user. 
Implement your propose model with KERAS.
C.	Calculate the MAE average for the test group for the model you suggested. 
Check for several parameter options Model (as explained above in 2.b) , and feature integration. 
D.	Compare your results using the different models: (which one the best? MAE, training time and more – show in table)
•	non-personalized  based on average rating for each movie
•	matrix factorized MF
•	general matrix factorized GMF
•	collaborative neural filtering CNF
•	model implemented with keras. 
E.	In summary, discuss the results, what is the model that you recommend to predict rating? Why?

