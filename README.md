# Deploying a Flask API

### Cluster Address

> a05a88ca9263548fe87eb0a3f4ac8c1f-1369455498.us-east-1.elb.amazonaws.com

This is a simple flask project to demonstrate my ability to deploy an app to AWS using Docker and Kubernetes through CodeBuild and CodePipeline.

## API Endpoints

- `GET '/'` : This is a simple health check, which returns the response 'Healthy'.
- `POST '/auth'` :  This takes a email and password as json arguments and returns a JWT based on a custom secret.
- `GET '/contents'` : This requires a valid JWT, and returns the un-encrpyted contents of that token.

