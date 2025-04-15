**Boosting** is an ensemble learning technique that combines multiple weak learners (usually decision trees) sequentially to create a strong learner.

Unlike bagging (where models are trained in parallel), boosting trains models one after another, and each new model focuses on fixing the errors made by the previous ones.

**🔁 How Boosting Works (Conceptually):**

Train a model on the data.

Identify which samples were misclassified.

Train a new model that focuses more on those "hard" samples.

Repeat the process, combining all models into a final, strong prediction.

Each model is weighted based on its performance, and predictions are combined in a weighted sum.

**🎯 Goal of Boosting:**

To reduce bias and variance, and build a powerful model that learns from the mistakes of previous models.

**🔥 Popular Boosting Algorithms:**

                 [Adaptive Boosting]    AdaBoost	  :    Adjusts weights of misclassified samples

                              Gradient Boosting	    :    Optimizes a loss function using gradient descent
                                  
        [Extreme Gradient Boosting]     XGBoost	    :    Faster, regularized version of Gradient Boosting
                                   
                                       LightGBM	    :    Optimized for speed and large datasets
                                  
                                       CatBoost	    :    Handles categorical data well, faster training

 






