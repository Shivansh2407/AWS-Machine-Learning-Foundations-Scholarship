## Test your knowledge with the following questions about Lesson 2: Introduction to Machine Learning

NOTE: **The questions might provide clues to the previous questions so skipping questions might ruin the experience.**

* In your own words, define Machine Learning
    <details>
      <summary>Show answer</summary>

      It is a method that allows computers to improve and learn using data.

      NOTE: any answer is acceptable as long as it states something about machines/computers learning/improving through data or finding patterns in data! The keyword is data!

    </details>

* What machine learning task deals with labeled data?
    <details>
      <summary>Show answer</summary>

      Supervised learning

    </details>

* What machine learning task deals with unlabeled data?
    <details>
      <summary>Show answer</summary>

      Unsupervised learning

    </details>

* What machine learning component is described as a generic program/block of code that is made specific by data?
    <details>
      <summary>Show answer</summary>

      Machine learning model or just the model

    </details>

* What do you call the iterative process of fitting a model to specific data
    <details>
      <summary>Show answer</summary>

      Model training

    </details>

* What do you call the process of using the trained model to generate predictions on input data?
    <details>
      <summary>Show answer</summary>

      Model inference

    </details>

* Re-order these steps according to the proper machine learning process:
  * Model evaluation
  * Model training
  * Define the problem
  * Use the model
  * Build the dataset
  <details>
    <summary>Show answer</summary>

    1. Define the problem
    2. Build the dataset
    3. Model training
    4. Model evaluation
    5. Use the model

  </details>

* In your own words, differentiate categorical labels to continuous labels
    <details>
      <summary>Show answer</summary>

      Categorical labels have a discrete/finite set of values. An example is the breed of a dog.

      Continuous labels have an infinite set of possible values, which often means it is numerical data. An example is the number of sold items.

    </details>

* True or False: The quality of your dataset will largely affect the performance of your trained model. Explain your answer.
    <details>
      <summary>Show answer</summary>

      True 
      
      Since models are made specific by data, if we use low quality data for our training -- our model will not perform well. 

    </details>

* What do you call the term referring to the use of different statistical tools to fill-in missing values from a dataset?
    <details>
      <summary>Show answer</summary>

      Impute

    </details>

* What do you call the data points that are significantly different from the others within the same dataset?
    <details>
      <summary>Show answer</summary>

      Outliers

    </details>

* What do you call the aspect of working with data that helps stakeholders understand your data (helps see outliers or trends in data)?
    <details>
      <summary>Show answer</summary>

      Data visualization

    </details>

* True or False: Data visualization is the only way to identify outliers in your data. Explain your answer.
    <details>
      <summary>Show answer</summary>

      False 
      
      We can also use statistics to check for outliers.

    </details>

* Before training our model, we split our dataset into two. What do you call the data set we use to train the model with?
    <details>
      <summary>Show answer</summary>

      Training dataset

    </details>

* Before training our model, we split our dataset into two. What do you call the data set we use to evaluate the performance of the trained model?
    <details>
      <summary>Show answer</summary>

      Test dataset

    </details>

* In your own words, explain what a model training algorithm basically does.
    <details>
      <summary>Show answer</summary>

      Use the training data to iteratively update model parameters to minimize some loss function

      Key processes:
      1. Feed training data to model / use the model to process the data
      2. Compute the value of the loss function based on the result
      3. Update model parameters in a direction that reduces the loss

    </details>

* In your own words, describe what a loss function is
    <details>
      <summary>Show answer</summary>

      A loss function is a measurement of how far the model is to the goal.

    </details>

* What do you call model parameters that can't be changed during training
    <details>
      <summary>Show answer</summary>

      Hyperparameters

    </details>

* True or False: You can always use model accuracy to evaluate your trained model. Explain your answer.
    <details>
      <summary>Show answer</summary>

      False

      Model evaluation metrics are tailored to a specific use case and should be thought about carefully. Not all metrics can be used to evaluate your trained model.

    </details>

* Clustering is an unsupervised machine learning task that finds naturally occuring groupings in data. Given this can you say that model inference involves finding patterns in data?
    <details>
      <summary>Show answer</summary>

      Yes

      Since in clustering, we figure out groupings in data only during model inference (because we don't know the actual groupings beforehand since they're not labeled) therefore we can say that we've only found the patterns in data during model inference.

      However, this does not mean that we always find patterns in data during model inference. For example, in classification (which is a supervised machine learning task), model inference generates predictions on the the type of class the input data belongs to (example: breed of dog). In this case we already know the breeds at the start.

    </details>