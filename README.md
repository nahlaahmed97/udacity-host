# Udagram

## Hosting link
The link to the application can be seen [here](http://nahla-udagram.s3-website.us-east-2.amazonaws.com/home).

## Info

This Udagram application was provided by Udacity. 

The first goal of this final project was to connect Udagram to Amazon Web Services:

- S3 (udagram-frontend) was used for hosting and posts
- Elastic Beanstalk was used for the API (udagram-api) 
- RDS was used for the `PostgreSQL` database 

The second goal of this project was to connect it with `CircleCI`. Any time this project's main branch is updated then the available application is immediately updated so that users get the latest and greatest features of Udagram.

## Installation

Run `npm install` to download the necessary dependencies.

## Running Udagram locally

You will need to create a `.env` file in `udagram-api` with the following variables set:
- AWS_ACCESS_KEY_ID
- AWS_DEFAULT_REGION
- AWS_SECRET_ACCESS_KEY
- JWT_SECRET
- POSTGRES_DB
- POSTGRES_HOST
- POSTGRES_PASSWORD
- POSTGRES_PORT
- POSTGRES_USERNAME
- PORT 
- URL

Open 2 terminal windows:
1. Navigate to `udagram-api` and run `npm run dev`
2. Navigate to `udagram-frontend` and run `npm run start`

Open `http://localhost:4200` in the browser.
