{% for _ in cookiecutter.project_name %}={% endfor %}
{{ cookiecutter.project_name }}
{% for _ in cookiecutter.project_name %}={% endfor %}


# This is the repository of the {{ cookiecutter.project_name }}



{{ cookiecutter.project_short_description }}


## What does the repository have?

* _/notebooks_
* _/src_
* _/utilities_
* _/api_
* _/dataset_
* _/model_
* _/.github/workflows_

### _/notebooks_

Notebooks where a compacted form of the results obtained.

### _/src_

This folder contains the files used to make the retraining Pipeline

### _/utilities_

This folder contains the files to set enverionment behaviour

### _/api_

The api folder contains all files related to the API service, it uses FastAPI as main framework

### _/dataset_

This folder is intended to save the dataset files, which are being tracked remotely using [Data Version Control](https://dvc.org/) and the .dvc files that have the hashes

### _/models_

As ```/dataset``` this folder contains de models files tracked with dvc

### _/.github/workflows_

This folder contains all workflow for continuous integration and deployment, testing and continuous training, used in github actions.

