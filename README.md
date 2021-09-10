# kubectl commnds
Folloiwng are some basic commands when working with k8s.

## Get nodes
kubectl get nodes

## Get pods
kubectl get pod

## Get Services
kubectl get services

## Create deployment.
kubectl create deployment nginx-depl --image=nginx 

## Get deployments.
kubectl get deployments

## Get replicasets.
kubectl get replicaset

## Get edit depolyment nginx-depl
kubectl edit deployment nginx-depl

# Debugging

# pod logs
kubectl logs {pod-name}

# Go to pod command line
kubectl exec -it {pod-name} -- bin/bash

# create mongo deployment
kubectl create deployment mongo-depl --image=mongo

kubectl logs mogo-depl-{pod-name}

kubectl describe pod mongo-depl-5fd6b7d4b4-bhqln

# Delete deployments
kubectl delete deployment mongo-depl

kubectl delete deployment nginx-depl

# Create or Edit conig file
vim nginx-deployment.yaml

kubectl appy -f nginx-deployment.yaml

kubectl get pods

kubectl get deployment

# delete with config
kubectl delete -f ngix-deployment.yaml

# Metrics
kubectl top