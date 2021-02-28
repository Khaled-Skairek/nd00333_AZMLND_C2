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
2. Experiment is complete
3. Best model
4. Application insights
5. Logs
6. Swagger runs on localhost
7. Endpoint
8. Apache benchmark
9. Pipeline
# Screencast
https://youtu.be/QWq_eiP9UXY
