# Mlops Pipeline
1. Data Injestion
2. Data Validation 
3. Data Transformation 
4. Model Training 
5. Model Evaluation 
6. Prediction Pipeline

After them we have 
7. User App 
8. Deploy App

## for creating an venv
conda create -n test python=3.11 -y
conda activate test

pip install requirements.txt



## for dvc we have to do these steps
git init

#### for initalising dvc
dvc init

#### for running the dvc 
dvc repro

#### for creating a diagram of how the pipeline will execute
dvc dag 