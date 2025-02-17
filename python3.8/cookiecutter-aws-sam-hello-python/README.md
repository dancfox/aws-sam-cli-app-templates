# Cookiecutter Python Hello-world for SAM based Serverless App

A cookiecutter template to create a Python Hello world boilerplate using [Serverless Application Model (SAM)](https://github.com/awslabs/serverless-application-model).

This template creates a Serverless Application that reacts to EC2 Instance State change events, demonstrating the power of event-driven development with Amazon EventBridge.


## Requirements

* [AWS SAM CLI](https://github.com/awslabs/aws-sam-cli)

## Usage

Generate a boilerplate template in your current project directory using the following syntax:

* **Python 3.7**: `sam init --runtime python3.7`
* **Python 3.6**: `sam init --runtime python3.6`

> **NOTE**: ``--name`` allows you to specify a different project folder name (`sam-app` is the default)


# Credits

* This project has been generated with [Cookiecutter](https://github.com/audreyr/cookiecutter)
