## Characteristics of Deployment and Modeling

Recall that : 

**Deployment** to production can simply be thought of as a method that integrates a ML model into an existing production environment so that the model can be used to make deicisions or predictions based upon data input into this **model**.

**Production environment** can be "any" software application that is currently being used by many people and must respond quickly to those users’ requests.

![ml_workflow](https://video.udacity-data.com/topher/2018/November/5bea55ad_mlworkflow-modeling-hyperparameter/mlworkflow-modeling-hyperparameter.png)

### Characteristics of Modeling

#### Hyperparameters

In machine learning, a hyperparameter is a parameter whose value cannot be estimated from the data.

+ Must be set by the model developer
+ Hyperparameter tuning for optimization is an important part of model training

Bonus :

[Scikit-learn](https://scikit-learn.org/stable/) is a free machine learning Python library that includes methods that help with hyperparameter tuning.

![ml_workflow](https://video.udacity-data.com/topher/2018/November/5bea55ad_mlworkflow-modeling-hyperparameter/mlworkflow-modeling-hyperparameter.png)

### Characteristics of Deployment

#### Model Versioning

One characteristic of deployment is the version of the model that is to be deployed, indicates the model's version deployed make it easier to mantain, monitor and update the deployed model.

#### Model Monitoring

Once a model is deployed you will want to make certain it continues performing metrics.

#### Model Updating and Routing

The ability to easily update your deployed model is another characteristic of deployment. If a deployed model is failing you will need to update this model.

Routing in this way allows for a test of a model performance as compared to other model variants.

#### Model Predictions

Another characteristic of deployment is the type of predictions provided by your deployed model. There are two common types of predictions:

+ On-demand predictions
  + online
  + real-time
  + synchronous predictions
+ Batch predictions
  + asynchronous
  + batch-based predictions

Batch predictions are commonly used to help make business decisions. For example, imagine a business uses a complex model to predict customer satisfaction across a number of their products and they need these estimates for a weekly report. This would require processing customer data through a batch prediction request on a weekly basis.












