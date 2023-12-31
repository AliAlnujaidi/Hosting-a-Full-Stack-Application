# Hosting a Full-Stack Application

## Description
 This project is a part of the Udacity Full-stack JavaScript Developer Nanodegree Program and it is a simple cloud-based photo sharing application. The application allows users to register and log into a web client, post photos to the feed and see the feed from other users.

## URLS
- Vists the website through this link: http://ali-udacity-project.s3-website-us-east-1.amazonaws.com/ 
- API URL: http://udagram-api-dev.eba-qfnipwm6.us-east-1.elasticbeanstalk.com/

## Get Started
Clone the repo, then navigate to the root of the repo and run the following commands:

To Run The project locally:
- To start the backend:
    - navigate to the backend folder - ```cd udagram/udagram-api```
    - Setup .env file
    - install dependencies - ```npm install --force```
    - Start the backend - ```npm run dev```

- To start Frontend:
    - navigate to the frontend folder - ```cd udagram/udagram-frontend```
    - install dependencies - ```npm install -f```
    - Start the frontend - ```npm run start```

## Env
```
AWS_ACCESS_KEY_ID
AWS_BUCKET
AWS_DEFAULT_REGION
AWS_PROFILE
AWS_REGION
AWS_SECRET_ACCESS_KEY
JWT_SECRET
POSTGRES_DB
POSTGRES_HOST
POSTGRES_PASSWORD
POSTGRES_PORT
POSTGRES_USERNAME
URL
```

### Dependencies
```
- Node v14.15.1 (LTS) or more recent. While older versions can work it is advisable to keep node to latest LTS version
- npm 6.14.8 (LTS) or more recent, Yarn can work but was not tested for this project
- AWS CLI v2, v1 can work but was not tested for this project
- A RDS database running Postgres.
- A S3 bucket for hosting uploaded pictures.

```

## Deployment procedure:

- RDS database.
- S3 Bucket for storing images from user.
- S3 Bucket for hosting Frontend.
- Elastic Beanstalk for hosting the API.


## Built With And Deployed

- [Angular](https://angular.io/) - Single Page Application Framework
- [Node](https://nodejs.org) - Javascript Runtime
- [Express](https://expressjs.com/) - Javascript API Framework
- [AWS](https://aws.amazon.com/) - Cloud Hosting Server

## License

[License](LICENSE.txt)