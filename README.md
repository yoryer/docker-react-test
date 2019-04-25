# CI/CD Workflow Test

The main goal of this project is learn how to deploy a single React Application to the AWS (Amazon Web Services) using TravisCI.

---

## What I learned?

+ Generate a React Application using the create-react-app package.

+ Create a Dockerfile (Dockerfile.dev) for a development environment and use it with docker-compose.

+ Push the code to a GitHub repository and use TravisCI to build a Docker image and test the code (only when the commit is pushed to the master branch).

+ Send the code from TravisCI to an AWS EB (Elastic Beanstalk).

+ Try the deploy results through the URL provided by the AWS EB.