# MLOps-Production-Pipeline

This is to show an end to end example of MLOps pipeline
===========================================================================

PROJECT STRUCTURE using template.py

USVisa/
├── __init__.py
│
├── components/
│   ├── data_ingestion.py
│   ├── data_validation.py
│   ├── data_transformation.py
│   ├── model_trainer.py
│   ├── data_evaluation.py
│   └── data_pusher.py
│
├── configuration/
│   └── __init__.py
│
├── constants/
│   └── __init__.py
│
├── entity/
│   ├── __init__.py
│   ├── config_entity.py
│   └── artifact_entity.py
│
├── exception/
│   └── __init__.py
│
├── logger/
│   └── __init__.py
│
├── pipeline/
│   ├── __init__.py
│   ├── training_pipeline.py
│   └── prediction_pipeline.py
│
├── utils/
│   ├── __init__.py
│   └── main_utils.py
│
├── app.py
├── demo.py
├── setup.py
│
├── config/
│   ├── model.yaml
│   └── schema.yaml
│
├── requirements.txt
├── Dockerfile
└── .dockerignore


=====================================================================
GIT COMMON HELP:

git clone https://github.com/Arnab0014/MLOps-Production-Pipeline.git
git status --> show the latest status of the files
git add .   --> add all files into git stash
git commit -m "first comment"  -> commits changes to the stash
git push origin main    --> push your changes to github repo
=====================================================================