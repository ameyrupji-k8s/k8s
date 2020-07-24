# Kubernetes

![GitHub deployments](https://img.shields.io/github/deployments/ameyrupji-k8s/k8s/github-pages?label=Pages&logo=GitHub)[`View Website`](https://ameyrupji-k8s.github.io/k8s/)

This repository is a starting place for documenting my kubernetes (k8s) learning journey. I have tried to capture these learnings by demonstrating 3 kinds of applications a static website, a web app using Java Spring Boot, and a cron job using Python. I will go through the process of taking these applications from the ground up, containerizing them using Docker, then deploying them to K8s cluster locally and on the cloud, adding the ability to scale them and performance test these applications.

## K8s Concepts

Use the following links to understand key k8s concepts

- https://medium.com/google-cloud/kubernetes-101-pods-nodes-containers-and-clusters-c1509e409e16
- https://medium.com/yld-blog/kubernetes-core-concepts-324ea7028c29
- https://medium.com/easyread/step-by-step-introduction-to-basic-concept-of-kubernetes-e20383bdd118
- https://kubernetes.io/docs/concepts/


## Presequisite

- Docker Desktop with k8s enabled

## My Learning

Lets start with understanding k8s building different kind of applications.

### Static Website

**[docker-nginx-static-html-demo](https://github.com/ameyrupji-k8s/docker-nginx-static-html-demo)**
Step by Step instructions to build and run a simple static HTML site with Docker and Nginx.

**[k8s-docker-nginx-static-html-demo](https://github.com/ameyrupji-k8s/k8s-docker-nginx-static-html-demo)**
Static html using nginx deployed on local Kubernetes.

### Java Spring Boot Web Applicaton 

**[spring-boot-helloworld](https://github.com/ameyrupji-k8s/spring-boot-helloworld)**
Basic Hello World Web Application in Java Spring Boot.

**[docker-spring-boot-helloworld](https://github.com/ameyrupji-k8s/docker-spring-boot-helloworld)**
Dockerizing Spring Boot hello world.

**[k8s-spring-boot-helloworld](https://github.com/ameyrupji-k8s/k8s-spring-boot-helloworld)**
Spring boot app deployed on local Kubernetes using helm.

**[k8s-spring-boot-helloworld-security-context](https://github.com/ameyrupji-k8s/k8s-spring-boot-helloworld-security-context)**
Security context defines privilege and access control settings for a Pod or Container.

[WIP] **[k8s/k8s-spring-boot-helloworld-scaling](https://github.com/ameyrupji-k8s/k8s-spring-boot-helloworld-scaling)**
Scaling the Spring Boot App Deployed on Local Kubernetes Cluster.

[WIP] **[k8s-spring-boot-helloworld-scaling-jmeter-performance-test](https://github.com/ameyrupji-k8s/k8s-spring-boot-helloworld-scaling-jmeter-performance-test)**
Adding jMeter test to create performance tests for testing autoscaling of pods.

[WIP] **[k8s-spring-boot-helloworld-service-accounts-aws](https://github.com/ameyrupji-k8s/k8s-spring-boot-helloworld-service-accounts-aws)**

[WIP] **[k8s-spring-boot-helloworld-service-accounts-azure](https://github.com/ameyrupji-k8s/k8s-spring-boot-helloworld-service-accounts-azure)**


### Python Cron Job 

**[python-helloworld](https://github.com/ameyrupji-k8s/python-helloworld)**
A simple python hello world script.

**[docker-python-helloworld](https://github.com/ameyrupji-k8s/docker-python-helloworld)**
Dockerizing python hello world script.

**[k8s-cronjob-python-helloworld](https://github.com/ameyrupji-k8s/k8s-cronjob-python-helloworld)**
Python hello world script deployed as a CronJob on local Kubernetes using helm.

**[k8s-cronjob-python-helloworld-security-context](https://github.com/ameyrupji-k8s/k8s-cronjob-python-helloworld-security-context)**
Adding Security Context to CronJob.

[WIP] **k8s-cronjob-python-helloworld-service-account-aws**


[WIP] **k8s-cronjob-python-helloworld-service-account-azure**


