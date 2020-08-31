# python-with-k8s-tools

Python base image with Kubernetes tools

# Base Image


python:3
- https://hub.docker.com/_/python


# Tools included

- AWS cli v2
- AWS aws-iam-authenticator
- Helm2
- Helm3
- Kubectl

# Building Image

The docker hub image are automatically built through the GitHub and Docker Hub integration
https://docs.docker.com/docker-hub/builds/

Manually build for local testing

- docker build -t python-with-k8s-tools .

