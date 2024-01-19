# Simple app using Docker and Kubernetes

**Build or rebuild services** based on the instructions in the `compose.yaml` file.

`docker compose build`

## Docker Desktop

**Create or update resources** in a Kubernetes cluster based on configuration files in ./kubernetes directory.

`kubectl apply -f ./kubernetes`

Go to [localhost:5001](localhost:5001) to see the application in action.

## minikube

When using **minkube**:

`minikube start`

`minikube tunnel` (in other terminal, has to work all the time)

`kubectl apply -f ./kubernetes`

Go to [localhost:5001](localhost:5001) to see the application in action.