# DockerComposeDatascience
Docker-Compose container with a python 3.8 enviroment for datascience with Jupyter Notebook

## Requirements
[Docker](https://docs.docker.com/get-docker/)  
[Docker-Compose](https://docs.docker.com/compose/install/)

## Usage
After you install docker and docker-compose all you have to do is open a terminal on the paste and type ``docker-compose up`` or ``sudo docker-compose up`` if you haven't configured docker to work without sudo. [How to configure Docker to run without sudo](https://docs.docker.com/engine/install/linux-postinstall/)

And you are done! The script will install python 3.8 and all the requirements in the [requirements.txt](https://github.com/tiagovalenca/DockerComposeDatascience/blob/master/requirements.txt) file. You can change the requirements to suit your needs, but don't forget to keep the ``jupyter==1.0.0`` for the Jupyter Notebook to be installed.

When the container installation is over it will run on [127.0.0.1/8888](127.0.0.1/8888) and you should be able to open it directly from your terminal. The default password to open the notebook is ``root`` and after you insert it you can start to work on your jupyter enviroment.

To stop the container all you have to do is type ``ctrl+c`` once on the terminal and wait till it is gracefully terminated or type ``ctrl+c`` twice to forcefully terminate it.

## Reference
This article was used as reference: [Docker + Jupyter for Machine Learning in 1 Minute](https://towardsdatascience.com/docker-jupyter-for-machine-learning-in-1-minute-30e1df969d09)
