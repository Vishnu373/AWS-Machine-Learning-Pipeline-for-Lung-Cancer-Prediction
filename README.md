# AWS-Machine-Learning-Pipeline-for-Lung-Cancer-Prediction

This project explored the effectiveness of AWS SageMaker for developing healthcare applications by building a lung cancer prediction model from scratch.

Data Preparation in S3: Raw medical data for lung cancer analysis can be complex. I leveraged SageMaker's capabilities to store the data in organized Amazon S3 buckets, separating training, testing, and validation sets. This clean, structured data became the foundation for the model.

Training a Linear Learner: I chose a linear learner algorithm within SageMaker. This type of algorithm excels at identifying linear relationships within the data, making it suitable for analyzing factors that might influence lung cancer risk. I trained the model using SageMaker's tools and resources.

Hyperparameter Tuning in the Cloud: Finding the optimal settings for the model is crucial. SageMaker's cloud-based tools allowed me to efficiently explore different configurations (hyperparameters) for the linear learner. This "tuning" process helped identify the settings that yielded the most accurate predictions for lung cancer.

Serverless Training with SageMaker Notebooks: I utilized SageMaker Notebooks in serverless mode to train the lung cancer prediction model. This streamlined approach allowed me to leverage the platform's resources without managing servers.
Through data cleaning, hyperparameter tuning, and model training within SageMaker, the model achieved an accuracy of 73.3%. 
