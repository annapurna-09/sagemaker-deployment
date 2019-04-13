# SageMaker Deployment Project
Project Overview

In this project, I used SageMaker to construct a complete project from end to end. The goal of this project is to have a simple web page which a user can use to enter a movie review. The web page will then send the review off to my deployed model which will predict the sentiment of the entered review.

Project Instruction

Clone the repository and navigate to the downloaded folder.
	git clone https://github.com/annapurna-09/sagemaker-deployment/Project/
	
	
Open the SageMaker Project.ipynb file. Of course, you can find HTML version of the file.
	jupyter notebook SageMaker Proejct.ipynb
	
Read and follow the instructions! You can find and download the dataset for this project in the notebook.


Project Information

General Outline
Step 1: Downloading the data
Step 2: Preparing and Processing the data
Step 3: Upload the data to S3
Step 4: Build and Train the PyTorch Model
Step 5: Testing the Model
Step 6: Deploying the model for testing
Step 7: Use the model for testing
Step 6 (again): Deploy the model for the web app
Step 7 (again): Use the model for the web app
Libraries
The list below represents main libraries and its objects for the project.

Amazon SageMaker (Build, train, and deploy a model)
PyTorch (LSTM classifier)
Delete the Endpoint
Remember to always SHUT DOWN YOUR ENDPOINT if you are no longer using it. You are charged for the length of time that the endpoint is running so if you forget and leave it on you could end up with an unexpectedly large bill.

	predictor.delete_endpoint()
