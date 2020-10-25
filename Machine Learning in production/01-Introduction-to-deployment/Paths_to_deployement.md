# Machine learning engineer Udacity nanodegree

![workflow](https://github.com/Adrianvegassanchez/machine-learning-engineer-udacity-nanodegree/blob/master/Introduction-to-deployment/workflow.png?raw=true)

## Deployment to Production

Method that integrates a ML Model into a existing production environment, this model can be used to make decisions or predictions based upon data input.

## Paths to Deployment

This are thre primary methods used to transfer a model from modeling component to the deployment component of the ML workflow : 

### Paths to Deployment:

+ Python model is recoded into the programming language of the production environment.
+ Model is coded in Predictive Model Markup Language (PMML) or Portable Format Analytics (PFA). 
+ Python model is converted into a format that can be used in the production environment.

**Recoding Model into Programming Language of Production Environment**

So much time to recode, test and validate the model that provides the same results as original. 
Rarely used.

**Model is Coded in PMML or PFA**

The second method is to code the model in Predictive Model Markup Language (PMML) or Portable Format for Analytics (PFA), which are two complementary standards that simplify moving predictive models to deployment into a production environment. 
The Data Mining Group developed both PMML and PFA to provide vendor-neutral executable model specifications for certain predictive models used by data mining and machine learning. Certain analytic software allows for the direct import of PMML including but not limited to IBM SPSS, R, SAS Base & Enterprise Miner, Apache Spark, Teradata Warehouse Miner, and TIBCO Spotfire.

**Model is Converted into Format that’s used in the Production Environment**

The third method is to build a Python model and use libraries and methods that convert the model into code that can be used in the production environment. Specifically most popular machine learning software frameworks, like PyTorch, TensorFlow, SciKit-Learn, have methods that will convert Python models into intermediate standard format, like ONNX (Open Neural Network Exchange format). This intermediate standard format then can be converted into the software native to the production environment.

+ This is the easiest and fastest way to move a Python model from modeling directly to deployment.
+ Moving forward this is typically the way models are moved into the production environment.
+ Technologies like containers, endpoints, and APIs (Application Programming Interfaces) also help ease the work required for deploying a model into the production environment.



