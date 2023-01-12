*NOTE:* This file is a template that you can use to create the README for your project. The *TODO* comments below will highlight the information you should be sure to include.


# Operationalizing Machine Learning
In this project, we will continue the work with the Bank Marketing dataset. We will use Azure to configure a cloud-based machine learning production model, deploy it, and consume it. We will also create, publish, and consume a pipeline.

## Architectural Diagram
The figure below shows steps that will be implemented in this project:
![image](./overview_project2.PNG)

## Key Steps
1. Authentication
Authentication means, we need to install the Azure Machine Learning Extension which allows us to interact with Azure Machine Learning Studio (part of the az command). After having the Azure machine Learning Extension, we create a Service Principal account and associate it with specific workspace.

Note: I am using provided project lab with authentication done, so I skiped this step.

2. Automated ML Experiment
In this step, We will create an experiment using Automated ML, configure a compute cluster, and use that cluster to run the experiment. We need to upload the dataset to Azure Machine Learning Studio so that it can be used when training the model.

3. Deploy the best model

4. Enable logging

5. Swagger Documentation

6. Consume model endpoints

7. Create and publish a pipeline

8. Documentation

## Screen Recording
*TODO* Provide a link to a screen recording of the project in action. Remember that the screencast should demonstrate:

## Standout Suggestions
*TODO (Optional):* This is where you can provide information about any standout suggestions that you have attempted.
