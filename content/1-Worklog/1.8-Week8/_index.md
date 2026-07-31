---
title: "Week 8 Worklog"
date: 2026-07-30
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
----------------------

### Week 8: Integrating a Machine Learning Model with AWS Lambda

**Duration:** 29/06/2026 – 05/07/2026

#### Objectives

* Learn how to integrate a Machine Learning model with a serverless architecture on AWS
* Practice deploying AWS Lambda using a container image stored in Amazon ECR
* Test the functionality of the backend API integrated with the Machine Learning model
* Explore methods for optimizing response time and operational costs

#### Tasks Completed

* Learned how to use Lambda container images to package the source code, Machine Learning model, and required libraries into a consistent deployment environment
* Studied the workflow for building a Docker image, storing it in Amazon ECR, and using the image to create or update a Lambda function
* Practiced deploying a Lambda function using a container image and tested the initialization and execution of the Machine Learning model
* Connected the Lambda function to an API endpoint and sent test requests to verify the backend's ability to process input data and return prediction results
* Explored methods for optimizing response time and operational costs, including reducing container image size, improving initialization time, and selecting appropriate resource configurations

#### Results Achieved

* Understood the workflow for integrating a Machine Learning model with AWS Lambda through a container image
* Successfully deployed a Lambda function using a container image stored in Amazon ECR
* Completed a backend API capable of receiving requests, running the Machine Learning model, and returning prediction results
* Gained a foundational understanding of the factors affecting response time and operational costs in a serverless system
