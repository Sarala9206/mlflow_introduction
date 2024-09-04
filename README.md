# mlflow_introduction

Section: 1 MLflow Introduction
Introduction to MLflow
What is MLflow?
MLflow is an open source platform for managing the machine learning lifecycle from start to finish.

MLflow is organized into four components: Tracking, Projects, Models, and Model Registry.Each of these components can be used independently. That means we can still track the model’s performance without exporting models in MLflow’s model format.

MLflow is designed to put as few constraints as possible and make codebase written in its format reproducible and reusable by multiple data scientists.

## Installation and first trial of MLflow
First create the conda environment by the following command -

conda create --prefix ./env python=3.7 -y
activate environment

conda actiavate ./env
To use MLflow as a Python library, install it using pip. You can install MLflow by running:

pip install mlflow
or
pip install requirements.txt


