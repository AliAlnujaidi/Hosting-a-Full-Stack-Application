# Pipeline
For the pipeline we are using CircleCI, the pipeline is divided into 3 stages:

## 1-Build
    - Spin up Environments
    - Preparing environments variables
    - Install Node
    - checkout code
    - Install Front-end Dependencies
    - Install API Dependencies
    - Frontend Lint
    - Frontend Build
    - API Build

## 2-Hold
    - the pipline waits for a manual approval to continue

## 3-Deploy
    - Spin up Environments
    - Preparing environments variables
    - Install Node
    - Setting up Elastic Beanstalk CLI
    - Install AWS CLI - latest
    - Configure AWS Access Key
    - Checkout code
    - Deploy App