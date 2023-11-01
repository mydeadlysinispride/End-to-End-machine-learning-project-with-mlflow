# End-to-End-machine-learning-project-with-mlflow

## Workflows

1. Update config.yaml
2. Update schema.yaml
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline 
8. Update the main.py
9. Update the app.py

# How to run?
### STEPS:

Clone the repository

```bash
https://github.com/mydeadlysinispride/End-to-End-machine-learning-project-with-mlflow
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n mlops python=3.9 -y
```

```bash
conda activate mlops
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```


```bash
# Finally run the following command
python app.py
```

Now,
```bash
open up you local host and port
```



## MLflow

[Documentation](https://mlflow.org/docs/latest/index.html)


##### cmd
- mlflow ui

### dagshub
[dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI=https://dagshub.com/namlc321/End-to-End-machine-learning-project-with-mlflow.mlflow \
MLFLOW_TRACKING_USERNAME=namlc321 \
MLFLOW_TRACKING_PASSWORD=6b359740ca369c46161f70ac4527e03dd974fa4b \
python script.py

Run this to export as env variables:

```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/namlc321/End-to-End-machine-learning-project-with-mlflow.mlflow

export MLFLOW_TRACKING_USERNAME=namlc321 

export MLFLOW_TRACKING_PASSWORD=6b359740ca369c46161f70ac4527e03dd974fa4b

```

for anaconda prompt:
```bash

set MLFLOW_TRACKING_URI=https://dagshub.com/namlc321/End-to-End-machine-learning-project-with-mlflow.mlflow

set MLFLOW_TRACKING_USERNAME=namlc321 

set MLFLOW_TRACKING_PASSWORD=6b359740ca369c46161f70ac4527e03dd974fa4b

```

