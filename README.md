# Deploy a Sentiment Analysis Model


### Project Introduction
This project is a small [Web App](https://en.wikipedia.org/wiki/Web_application), based on [Amazon SageMaker](https://aws.amazon.com/de/sagemaker/), which can be used to easily and quickly predict whether a review is `positive` or `negative`. 





With the [Sentiment Analysis Web App](website/index.html), the review text can be analyzed to determine whether it is positive or negative (*Assumes that the corresponding model endpoint is enabled in Amazon SageMaker!*).
The original review text can be cut and pasted into the review input field of the Web App. When you click on the Submit button, the system displays a prediction as to whether the review is to be considered `positive` or `negative`:

![title](test/2.PNG)


### Model Building and Deployment
The Jupyter Notebook [SageMaker Project](SageMaker%20Project.ipynb) explains how the model was created, tested and deployed using Amazon SageMaker.
The result is also shown in the [report.html](report.html) file.


#### Marizu-Ibewiro Makozi