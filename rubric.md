### Project Specification

## Deploying a Sentiment Analysis Model

### Files Submitted
Criteria 	Meets Specifications

Submission Files
	

The submission includes all required files, including notebook, python scripts, and html files.

### Preparing and Processing Data
Criteria 	Meets Specifications

Question: What does review_to_words do?
	

Answer describes what the pre-processing method does to a review.

Question: What are the five most frequently appearing words?
	

Notebook displays the five most frequently appearing words.

Create a word dictionary
	

The build_dict method is implemented and constructs a valid word dictionary.

Question: Understanding preprocess_data and convert_and_pad_data
	

Answer describes how the processing methods are applied to the training and test data sets and what, if any, issues there may be.

### Build and Train a PyTorch Model
Criteria 	Meets Specifications

Writing the training method
	

The train method is implemented and can be used to train the PyTorch model.

Training the model
	

The RNN is trained using SageMaker's supported PyTorch functionality.

### Deploy a Model for Testing
Criteria 	Meets Specifications

Deploy the trained model
	

The trained PyTorch model is successfully deployed.

### Use the Model for Testing
Criteria 	Meets Specifications

Question: How does this model compare to the XGBoost model?
	

Answer describes the differences between the RNN model and the XGBoost model and how they perform on the IMDB data.

Process the test review
	

The test review has been processed correctly and stored in the test_data variable.

Writing inference code
	

The predict_fn() method in serve/predict.py has been implemented.

### Deploying a Web App
Criteria 	Meets Specifications

The web app is deployed
	

The model is deployed and the Lambda / API Gateway integration is complete so that the web app works (make sure to include your modified index.html).

Question: Give an example review and response
	

Answer gives a sample review and the resulting predicted sentiment.

---


### Suggestions to Make Your Project Stand Out!
(1) Make a Better Web App

The web app that you make in this project simply reports to the user whether the predicted sentiment was positive or negative. Can you think of a better web app that uses the same model?

(2) Improve the Web App Appearance

The provided web app is very simple and there is plenty of room for improvement if you wish to stretch your web developer skills.

(3) Improve the Model

The model chosen here is a straightforward RNN with a single hidden layer. There are many different model architectures that you could try to see if they improve the results.
