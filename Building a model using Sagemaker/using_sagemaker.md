## Usin g SageMaker

### SageMaker Sessions & Execution Roles :

+ **Session** - A session is a special object that allows you to do things like manage data in S3 and create and train any machine learning models.
The <code>upload_data</code> function should be close to the top of the list! You'll also see functions like <code>train</code>, <code>tune</code>, and <code>create_model</code>.
+ **Role** - Sometimes called the execution role, this is the IAM role that you created when you created your notebook instance. The role basically defines how data that your notebook uses/creates will be stored. You can even try printing out the role with print(role) to see the details of this creation.

### Uploading to an S3 Bucket


S3 is a virtual storage solution that is mostly meant for data to be written to few times and read from many times. This is, in some sense, the main workhorse for data storage and transfer when using Amazon services. These are similar to file folders that contain data and metadata about that data, such as the data size, date of upload, author, and so on.

After you upload data to a session, you should see that an S3 bucket is created, as indicated by an output like the following:

    INFO: sagemaker: Created S3 bucket: <message specific to your locale, ex. sagemaker-us-west-1-#>

