## Amazon Web Services (AWS)

[Amazon Web Services (AWS) SageMaker](https://aws.amazon.com/es/sagemaker/) is Amazon's cloud service that allows you to build, train, and deploy machine learning models

+ **Flexibility** (Software) to use any programming language or framework, there are three methods of modeling :
  + **Built-in Algorithms** : At least fifteen built-in algorithms in SageMaker, for discrete classification, quantitative analysis, item recomendation, image classification etc.
  + **Custom Algorithms** : You can use some frameworks to develop custom algorithms PyTorch, TensorFlow, Apache MXNet, Apache Spark and Chainer.
  + **Your own Algorithms** : Use your own algorithm

+ **Ability to Explore and Process Data within SageMaker** : enables the use of Jupyter Notebooks to explore and process data, along with creation, training, validation, testing, and deployment of machine learning models. 

+ **Flexibility in Modeling and Deployment**  : Sagemaker provides features and automated tools that make modeling and deployment easier.
  + [Automatic Model Tuning](https://docs.aws.amazon.com/sagemaker/latest/dg/automatic-model-tuning.html) provides hyperparameter tuning to find the best version of the model for built-in and custom algorithms.SageMaker also provides evaluation metrics to evaluate the performance of your models.
  + [Monitoring Models](https://docs.aws.amazon.com/sagemaker/latest/dg/monitoring-overview.html) : Features to monitor your deployed models.Additionally with model deployment, one can choose how much traffic to route to each deployed model (model variant). 
  + Type of Predictions : by default allows for On-demand type of predictions where each prediction request can contain one to many requests. SageMaker also allows for Batch predictions, and request data size limits are based upon S3 object size limits.

## Google Cloud Platform (GCP)

[Google Cloud Platform (GCP)](https://cloud.google.com/ml-engine/) ML Engine is Google's cloud service that allows you to build, train, and deploy machine learning models. 

## Microsoft Azure
Similar to Amazon's SageMaker and Google's ML Engine, Microsoft offers [Azure AI](https://azure.microsoft.com/en-us/overview/ai-platform/#platform). Azure AI offers an open and comprehensive platform that includes AI software frameworks like: TensorFlow, PyTorch, scikit-learn, MxNet, Chainer, Caffe2, and other software like their Azure Machine Learning Studio. For more details see Azure AI and Azure Machine Learning Studio.

## Paperspace
[Paperspace](https://www.paperspace.com/ml) simply provides GPU-backed virtual machines with industry standard software tools and frameworks like: TensorFlow, Keras, Caffe, and Torch for machine learning, deep learning, and data science. Paperspace claims to provide more powerful and less expensive virtual machines than are offered by AWS, GCP, or Azure.

## Cloud Foundry
[Cloud Foundry](https://www.cloudfoundry.org/) is an open source cloud application platform that's backed by companies like: Cisco, Google, IBM, Microsoft, SAP, and more. Cloud Foundry provides a faster and easier way to build, test, deploy, and scale applications by providing a choice of clouds, developer frameworks, and applications services to it's users. Cloud Foundry Certified Platforms provide a way for an organization to have their cloud applications portable across platforms including IBM and SAP cloud platforms.