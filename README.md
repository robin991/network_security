# Network Security MLOps Project
## Project Overview

This project aims to develop, train, and test machine learning models for network security using MLOps practices. The project is structured to facilitate seamless integration, continuous development, and deployment of ML models in a production environment.
Directory Structure

The following is the directory structure of the project, along with a brief description of each folder's purpose:
1. Artifacts/

    Purpose: This directory contains all the artifacts generated during the training and testing process, such as model outputs, logs, and temporary files.

2. NetworkData/

    Purpose: This folder stores the network data used for training and testing the models. It includes raw and processed datasets.

3. Notebook/

    Purpose: This directory contains Jupyter notebooks used for Exploratory Data Analysis (EDA). The notebooks help in understanding data patterns, relationships, and distributions before model training.

4. Airflow/

    Purpose: This folder contains configuration files, DAGs (Directed Acyclic Graphs), and other components required to automate and schedule the ML pipeline using Apache Airflow.

5. Data_Schema/

    Purpose: This directory holds YAML files that define the schema of the data, ensuring that the data used in the pipeline adheres to a consistent format.

6. NetworkSecurity/

    Purpose: This folder includes various components essential for the ML pipeline, such as:
        Components: Core modules that handle data ingestion, transformation, and model training.
        Constant: Constants and configuration variables used across the project.
        Entity: Data classes and other entities used in the pipeline.
        Logger: Logging utilities to track the execution of different modules.
        Pipeline: Scripts that define the end-to-end ML pipeline.
        Utils: Utility functions and helper scripts.
        Exception: Custom exception handling classes to manage errors gracefully.

7. Saved_Model/

    Purpose: This directory contains the final trained and validated model, ready to be deployed into production.

## Execution

The project execution begins with the start_training.py file. This script initiates the training pipeline, leveraging the modules and configurations defined in the project directories.