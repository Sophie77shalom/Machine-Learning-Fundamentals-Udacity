## Project: Build a ML Workflow For Scones Unlimited On Amazon SageMaker

In this project, I will develop and deploy an image classification model for Scones Unlimited, a logistics company focused on scone delivery. The goal is to create a model that can automatically detect the type of vehicle used by delivery drivers (bicycle or motorcycle) to optimize routing and operations.

The image classification model will assist in multiple ways, such as:

Detecting people and vehicles in video feeds from roadways.
Supporting social media engagement.
Detecting defects in scones.
Optimizing delivery routing based on the type of vehicle.
By assigning nearby orders to delivery professionals with bicycles and farther orders to motorcyclists, Scones Unlimited can streamline its operations and improve efficiency.

Project Steps
Data Staging:

Collect and preprocess a dataset of images containing bicycles and motorcycles.
Perform data augmentation and normalization to prepare the data for training.
Model Training and Deployment:

Use AWS SageMaker to build and train an image classification model that distinguishes between bicycles and motorcycles.
Deploy the trained model on SageMaker to make it accessible for real-time predictions.
Lambdas and Step Function Workflow:

Develop AWS Lambda functions to create supporting services for the model.
Use AWS Step Functions to compose the model and services into an event-driven application.
Testing and Evaluation:

Test the deployed model to ensure it accurately classifies vehicle types.
Evaluate the model's performance and make necessary adjustments.
Optional Challenge:

Implement additional features or improvements to the model and workflow to further optimize performance.