# Overview
In this project, the following two tasks are done:
## Model as a service
A machine learning model is trained and deployed to be used as a web service. To get that model, an auto ML pipeline is created and run using Azure Python SDK.  
Once the run is complete, the best model can be deployed using Azure ML studio. As a result, URI to the model is provided, along with a swagger json,  so the model can ba called using HTTP.
## Pipeline as a service
Machine learning pipeline is created and published in the same way as the model above to get a REST API, so the pipeline can be consumed using HTTP as well.
# Architecture
![Architecture](images/Architecture.png)
# Improve the project
1. Split the notebook into two parts, one for the model and one for the pipeline
2. Let the student do some coding would be nice
# Screenshots
Here we will go through the steps of the project along with the screenshots of functioning steps.  
1. Dataset of the bankmarketing is registrered in Azure ML  
![Registered dataset](images/01_Registered_datasets.png)
3. Experiment is complete
![Experiment is complete](images/02_automl_completed.png)
5. Best model
![Best model](images/03_automl_best_model.png)
7. Application insights
![Application insights](images/04_application_insights.png)
9. Logs
![Logs](images/05_logs_1.png)
![Logs](images/06_logs_2.png)
11. Swagger runs on localhost
![Swagger runs on localhost](images/swagger_best_model.png)
13. Endpoint
14. Apache benchmark
15. Pipeline
# Screencast
https://youtu.be/QWq_eiP9UXY
