# Deploy Grafana on Kubernetes

## Requirements

 - [K8s cluster](https://kubernetes.io/docs/tasks/tools/)

## Deploy manifest to Kubernetes server

Run the following command: 
````
kubectl apply -f grafana.yaml
````

Check that it worked by running the following: 
````
kubectl port-forward service/grafana 3000:3000
````
Navigate to localhost:3000 in your browser. You should see a Grafana login page.

Use admin for both the username and password to login.