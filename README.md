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

Manually build for local testing

- docker build -t python-with-k8s-tools .

Manually push to DigitalRoute Docker Hub

- docker login
- docker build -t digitalroute/python-with-k8s-tools:<version> .
- docker push digitalroute/python-with-k8s-tools:<version>

# Run Image

- docker run -it --rm --privileged digitalroute/python-with-k8s-tools:<version> bash
