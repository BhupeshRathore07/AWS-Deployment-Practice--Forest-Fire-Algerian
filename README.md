

# AWS Deployment Practice - Forest Fire Algerian

This repository contains the code and necessary files to deploy a Flask web application to AWS using Elastic Beanstalk. The application is a simple model to predict the burned area of forest fires in Algeria based on the input parameters like temperature, wind, relative humidity, etc.

## Files

- `application.py`: This is the main Flask application file.
- `model.pkl`: This is the serialized Random Forest Regression model that has been trained on the forest fire dataset.
- `requirements.txt`: This file contains the list of packages required to run the application.
- `.ebextensions/`: This directory contains configuration files for Elastic Beanstalk.

## Usage

To run the application locally, you will need to have Python 3 installed. Clone this repository and run the following commands:

```bash
pip install -r requirements.txt
python application.py
```

Open a browser and go to `http://localhost:5000` to view the application.

To deploy the application to AWS Elastic Beanstalk, follow the steps mentioned in the official [AWS Elastic Beanstalk documentation](https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/GettingStarted.html).

## License

This project is licensed under the MIT License - see the LICENSE file for details.

### ENJOY DATA SCIENCE 'N' CODING 🐍😎
