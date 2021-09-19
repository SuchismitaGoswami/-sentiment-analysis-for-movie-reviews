# Sentiment-analysis-for-movie-reviews
Sentiment analysis for movie reviews Project is a part of Udacity Deep Learning Nanodegree.

# Project Overview

In this project, I built a LSTM network for the purpose of determining the sentiment of a movie review using the IMDB data set. The model was developed leveraging Amazon's SageMaker service amd deployed as endpoint. In addition, I constructed a simple web app which will interact with the deployed model via API Gateway. The API Gateway invokes an AWS Lambda which run the evaluation/testing by accessing the endpoint. 

# Sample result
Following are some of the sample result based on some sample moview reviews.

### Positive review
![Alt text](src/images/positive.PNG?raw=true "positive review")

### Negative review
![Alt text](src/images/negative.PNG?raw=true "negative review")

# Technology Used
- Python Frameworks (NumPy, Pytorch, OpenCV, Matplotlib, etc.)
- Long short-term memory
- Amazon Services (AWS SageMaker, Amazon API Gateway, AWS Lamda, Amazon S3, XGBoost notebook)


# References
- Further reading on tokenization https://nlp.stanford.edu/IR-book/html/htmledition/tokenization-1.html
- More reading on bringing your own algorithms and running them on AWS infrastructure https://docs.aws.amazon.com/sagemaker/latest/dg/your-algorithms-training-algo.html
- XGBoost https://docs.aws.amazon.com/sagemaker/latest/dg/xgboost.html is provided by aws out-of-the-box.In our case we have used our own algorithm and our own containers to do the training which shows the flexibility of sagemaker as a platform to bring our own algorithms and perform training.


