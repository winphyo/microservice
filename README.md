https://app.circleci.com/pipelines/github/winphyo

## Project Overview

There is a model that  predict housing prices in Boston according to several features, such as average rooms in a home and data about highway access, teacher-to-pupil ratios, and so on. The `app.py`—that serves out predictions (inference) about housing prices through API calls. 

## Docker Hub Location for this project
[https://hub.docker.com/repository/registry-1.docker.io/wpthein/microservice/](https://hub.docker.com/repository/registry-1.docker.io/wpthein/microservice/)

### Project Tasks

This project goal is to operationalize this working, machine learning microservice using [kubernetes](https://kubernetes.io/) In this project I have done:
* Test  project code using linting
* Complete a Dockerfile to containerize this application
* Deploy  containerized application using Docker and make a prediction
* Improve the log statements in the source code for this application
* Configure Kubernetes and create a Kubernetes cluster
* Deploy a container using Kubernetes and make a prediction
* Upload a complete Github repo with CircleCI 

## Setup the Environment

* Create a virtualenv and activate it
* Run `make install` to install the necessary dependencies

### Running `app.py`

1. Standalone:  `python app.py`
2. Run in Docker:  `./run_docker.sh`
3. Run in Kubernetes:  `./run_kubernetes.sh`

### Kubernetes Steps

* Setup and Configure Docker locally
* Setup and Configure Kubernetes locally , Since I am having window I have install minikube and use the kubectl to test this setup.
* Create Flask app in Container
* Run via kubectl 
