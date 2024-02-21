# Operationalizing-an-AWS-ML-Project
This project showcases the process of operationalizing a machine learning model on AWS, focusing on a dog breed classification system. The project includes steps from training the model using SageMaker, deploying it for inference, and integrating it with AWS Lambda for easy access.

### Project Structure
The project involves several key components:
1. SageMaker Notebook Instance: Utilized for initial model development and experimentation.
2. S3 Bucket: Stores the dog breed dataset and model artifacts.
3. EC2 Instance: For additional model training and experimentation outside SageMaker.
4. Lambda Function: Handles invocation of the deployed model endpoints for inference.
5. Model Training and Deployment: Utilizes SageMaker for training the model and deploying it as a scalable endpoint.
6. Python Scripts: Includes scripts for model training (ec2train1.py), hyperparameter optimization (hpo.py), and inference (inference2.py).

### Key Features
- SageMaker for Model Training: Leverages the power of AWS SageMaker for efficient model training and deployment, utilizing ml.m5.xlarge instances for hyperparameter tuning and deploying endpoints for model inference.
- EC2 for Additional Training: A t2.xlarge EC2 instance, equipped with an Amazon Deep Learning AMI, is used for further model training, demonstrating the flexibility of AWS services in supporting ML workflows.
- Lambda for Model Invocation: A Python 3 AWS Lambda function is used to invoke the model, allowing for easy integration and scalability within AWS infrastructure.
- Hyperparameter Optimization and Auto-scaling: Details the use of hyperparameter optimization for model training and auto-scaling for the deployed endpoint to manage load efficiently.

### Conclusion
This project illustrates a comprehensive approach to operationalizing a machine learning model on AWS, from data storage and model training to deployment and inference. By leveraging AWS services like SageMaker, EC2, and Lambda, one can create scalable and efficient ML systems.
