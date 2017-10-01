# Pandas & Numpy in AWS Lambda with python 3.6

This python deployment package allows you to run pandas and numpy in AWS Lambda with python 3.6 runtime.

Clone the repo and then simply add your `lambda_function.py` to the zip file by running:

```zip -ur lambda.zip YOUR_LAMBDA_FUNCTION.py```

Upload the zip file to S3 and source to lambda.

Enjoy!