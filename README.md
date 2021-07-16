# python-helloworld
## Udacity SUSE Cloud Native Fundamentals

This repository includes the assets for the exercise in Lesson 5: CI/CD with Cloud Native Tooling.

Create a GitHub Action in the `./github/workflows/docker-build.yml` that will build and push the Docker image for a [Python web application](https://github.com/udacity/nd064_course_1/tree/main/exercises/python-helloworld) with the following requirements:
* image name: `python-helloworld`
* tag: `latest`
* platforms: `platforms: linux/amd64, linux/arm64`

The above GitHub Action uses DockerHub Tokens and encrypted GitHub secrets to log in to DockerHub and push new images. To set up these credentials, refer to the following resources:
* Create [DockerHub Tokens](https://www.docker.com/blog/docker-hub-new-personal-access-tokens/)
* Create [GitHub encrypted secrets](https://docs.github.com/en/free-pro-team@latest/actions/reference/encrypted-secrets)
