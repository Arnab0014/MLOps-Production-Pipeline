# MLOps-Production-Pipeline

This is to show an end to end example of MLOps pipeline

Project Structure generated using template.py

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
