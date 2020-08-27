## Containers

![containers](https://video.udacity-data.com/topher/2018/November/5bea677a_m6-l1-c04-endpoint/m6-l1-c04-endpoint.png)

### Model, Application, and Containers

Containers are one way to create and maintain computing environments where model and application can be run and available for use.

Containers are created using a script thath contains instructions on which software packages, libraries and other computing attributes are needed to run an application, in this case model and application.

Def: A container can be thought of as a standardized collection/bundle of software that is to be used for the specific purpose of running an application.

### Container Structure

+ Computational infrastructure, can be a cloud provider's data center, an on-premise data center, or even someone`s local computer.
+ OS, that is running on this computational infrastructure, this could be the os on your local computer.
+ Container Engine, this part enables create, save, use and delete containers, for example Docker running on a local computer.
+ At the top, we see two layers one to contain the libraries and binaries requires to launch, run, and maintain the top layer, the app layer.

![containers](https://video.udacity-data.com/topher/2018/November/5bea67ba_container-1/container-1.png)

Architecture of containers advantages : 

+ Isolates the app, increasing security
+ Requires only software needed to run the app, using resources more efficiently and allows faster app deployment.
+ Makes application creation, replication, deletion, and maintenance easier and the same across all applications that are deployed using containers. Thats useful to replicate a particular container sharing the script file that is simply the instructions that is used to create a container, in docker are called dockerfiles.
+ Provides a more simple and secure way to replicate, save, and share containers.

Bonus :
For Docker, the [Docker Hub](https://hub.docker.com/explore/) is the official repository for storing and sharing dockerfiles. Here's an example of a [dockerfile](https://github.com/pytorch/pytorch/blob/master/docker/pytorch/Dockerfile) that creates a docker container with Python 3.6 and PyTorch installed.


