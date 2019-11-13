# movie-model
There are about 4000+ rows and 16 columns in the movie dataset. Cvt_per_day is a measure on how much a movie is consumed by the audiences per day. Higher number means the movie is more popular on our platform.
In this project, I need to build a prediction model to predict whether a movie is going to perform well on our platform (cvt_per_day) based on the information in the dataset.
My process:
1. Load data from google drive folder
2. Explore data
  2.1 Remove duplicates
  2.2 Understand the numeric features
    2.2.1 Explore missing values
    2.2.2 Explore target feature
    2.2.3 Explore correlation among numerical features
  2.3 Understand categorical features
    2.3.1 Explore some simple features
    2.3.2 Explore 'genre' feature
    2.3.3 Explore 'release_year' feature
 3. Feature preprocessing
   3.1 Categorical features (one hot encoding)
   3.2 Handling missing value
   3.3 Feature scaling
 4. Model Training
   4.1 Linear models 
    4.1.1 Lasso (Polynomial = 1,2)
    4.1.2 Ridge (Polynomial = 1,2)
   4.2 Nonlinear model
    4.2.1 Random forest
 5. Model evaluation (result: random forest fits best)
 6. Feature importance
    
