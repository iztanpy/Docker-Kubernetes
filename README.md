# CS3219 OTOT Task A2 and A3

This repository contains my solution to Task A2 and A3. This repo is able to successfully deploy an image with docker and scale with kubernetes. More information and a comprehensive tutorial can be found below, and in the relevant folders listed.


## A2 - Introduction to Kubernetes

This assignment has three parts:
* A2.1 Deploy a local k8s cluster
* A2.2 Deploy your A1 Docker image as Deployment in A2.1 cluster
* A2.3 Deploy Ingress to expose A2.2 Deployment to your localhost

Follow the guide in demo/a2/ to complete the tasks.
Place your manifests in k8s/manifests/ and commands used in k8s/a2_setup.sh.

## A3 - Scalability and Availability

This assignment has two parts:
* A3.1 Deploy HorizontalPodAutoscaler that makes A2.2 Deployments scale up under load.
* A3.2 Modify your A2.2 Deployment to be distributed equally in each zone


Follow the guide in demo/a3/ to complete the tasks.
Place your manifests in k8s/manifests/ and commands used in k8s/a3_setup.sh.
