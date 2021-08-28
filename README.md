# kubectl commnds

## Get nodes
kubectl get nodes

## Get pods
kubectl get pod

## Get Services
kubectl get services

## Create deployment.
kubectl create deployement --image=nginx nginx-depl

## Get deployments.
kubectl get deployments

## Get replicasets.
kubectl get replicaset

## Get edit depolyment nginx-depl
kubectl edit deployment nginx-depl

# Debugging

# pod logs
kubectl logs {podname}

# Go to pod command line
kubectl exec -it {podname} -- bin/bash

## create mongo deployment


