# This is the repository of the Introduction to the deployment of Machine Learning Models Course At Platzi

[Here is the link of the course](https://platzi.com/cursos/ml-ops/)

All code in the repository is intended to replicate the behavour of machine learning models lifecycle in production.

Having in mind that I wil make Continuous Integration, Deployment and Training, also it test the API using github actions.


## What does the repository have?

* _/notebooks_
* _/src_
* _/utilities_
* _/api_
* _/dataset_
* _/model_
* _/.github/workflows_

### _/notebooks_

Notebooks where a compacted form of the results obtained in [applied machine learning with python course of Platzi](https://platzi.com/clases/scikit/) can be seen

### _/src_

This folder contains the files used to make the retraining Pipeline

### _/utilities_

This folder contains the files to set enverionment behaviour

### _/api_

The api folder contains all files related to the API service, it uses [FastAPI](https://fastapi.tiangolo.com/) as main framework

### _/dataset_

This folder is intended to save the dataset files, which are being tracked remotely using [Data Version Control](https://dvc.org/) and the .dvc files that have the hashes

### _/models_

As ```/dataset``` this folder contains de models files tracked with dvc

### _/.github/workflows_

This folder contains all workflow for continuous integration and deployment, testing and continuous training, used in github actions.



You can test the API [here](https://deployment-intro-ml-service-tkjyn7djeq-uc.a.run.app)

Also yo can reach me in Twitter as [@gersonrpq](https://twitter.com/gersonrpq)
