# MLflow Project
## Concepts Used:
1. Modular Programming
2. MLOps

## Concepts which can be used:
1. FrameWorks like Flask, DJango, StreamLit
2. Cloud(AWS)

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

Index.html

<img width="767" alt="image" src="https://github.com/ddhruvin/MLFlow/assets/120237476/1d553a2b-c098-4289-a7ff-d5bac63ca978">

MLFlow o/p

<img width="831" alt="image" src="https://github.com/ddhruvin/MLFlow/assets/120237476/6ebe352b-47de-4ca7-9e29-2e2893c8f33b">

It clearly shows that best parameter values are: alpha:0.2, l1-ratio: 0.1.

Because we want low rsme(Root Mean Square Error), high r^2(Coefficient of determination) and low mae(Mean Absolute Error)

# How to run?
### STEPS:

Clone the repository

```bash
https://github.com/ddhruvin/MLFlow.git```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n mlproj python=3.8 -y
```

```bash
conda activate mlproj
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


## About MLflow 
MLflow

 - Its Production Grade
 - Trace all of your expriements
 - Logging & tagging your model


