# Heart disease prediction
---
[This project](https://github.com/gfa61-ga/heart-disease-prediction/blob/master/project-report.pdf) is a python notebook that applies machine learning algorithms and techniques to create a heart disease estimator, using 13 patient features as inputs.
* age
* sex
* chest pain type
* resting blood pressure
* serum cholestoral in mg/dl
* fasting blood sugar > 120 mg/dl
* resting electrocardiographic results
* maximum heart rate achieved
* exercise induced angina
* ST depression induced by exercise relative to rest
* the slope of the peak exercise ST segment
* number of major vessels (0-3) colored by flourosopy
* thallium test result

## Installation and Run

To run the notebook:
1. [Create an AWS Account](https://aws.amazon.com/premiumsupport/knowledge-center/create-and-activate-aws-account/)
2. Login to the AWS managment console
3. [Create an Amazon S3 Bucket](https://docs.aws.amazon.com/sagemaker/latest/dg/gs-config-permissions.html)
4. [Create an Amazon SageMaker Notebook Instance](https://docs.aws.amazon.com/sagemaker/latest/dg/gs-setup-working-env.html)
5. In 'Git repositories' optional section chooze 'Clone a public Git repository to this notebook instance only' and add 'https://github.com/gfa61-ga/heart-disease-prediction' at Git repository URL
6. Start the notebook instance
7. Click on 'Heart Disease Prediction.ipynb' file to open this project's notebook and run it on a python 3.6 kernel




## Dependencies
This notebook is using the following additional packages:
* [os](https://pypi.org/project/os-utils/) - Os utils for python
* [pandas](https://pypi.org/project/pandas/) - Powerful data structures for data analysis, time series, and statistics
* [glob](https://pypi.org/project/glob2/) - Filename pattern matching
* [numpy](https://pypi.org/project/numpy/) - The fundamental package for array computing with Python
* [seaborn](https://pypi.org/project/seaborn/) - Statistical data visualization
* [matplotlib.pyplot](https://pypi.org/project/matplotlib/) - Python plotting package
* [boto3](https://pypi.org/project/boto3/) - The AWS SDK for Python
* [sagemaker](https://pypi.org/project/sagemaker/) - Open source library for training and deploying models on Amazon SageMaker.


## License
This code is distributed under the [MIT license](https://opensource.org/licenses/MIT).
