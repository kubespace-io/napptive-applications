# Deploy Vault on Kubernetes

## Requirements

 - [K8s cluster](https://kubernetes.io/docs/tasks/tools/)

## Deploy manifest to Kubernetes server

Run the following command: 
````
kubectl apply -f vault.yaml
````

Check that it worked by running the following: 
````
kubectl port-forward service/vault-system 8200:8200
````
Navigate to http://127.0.0.1:8200 in your browser. You should see a Vault login page.
