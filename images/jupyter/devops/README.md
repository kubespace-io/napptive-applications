# Jupyter-DevOps

[![image-jupyter-devops](https://github.com/kubespace-io/napptive-applications/actions/workflows/image-jupyter-devops.yml/badge.svg)](https://github.com/kubespace-io/napptive-applications/actions/workflows/image-jupyter-devops.yml)
![Docker Pulls](https://img.shields.io/docker/pulls/kubespacedev/jupyter-devops?logo=docker&logoColor=white)

## 1. Features

This image is a modification of the official [jupyter/tensorflow-notebook](https://hub.docker.com/r/jupyter/tensorflow-notebook) image. 

The following components have been added:

| CLI Components | Infrastructure Components | Python libraries |
|---| ---| ---|
| Azure CLI | 	Terraform | pyodbc==4.0.34 |
| AWS CLI | Ansible | mysql-connector-python==8.0.33 |
| Napptive CLI | kubectl | psycopg2==2.9.6 |
| | | hvac==1.1.1 |
| | | azure-identity==1.13.0 |
| | | azure-keyvault-secrets==4.7.0 |

## 2. Image tags

You can download the full image from [Docker Hub](https://hub.docker.com/) with the following command.

````
docker pull kubespacedev/jupyter-devops:latest
````
````
docker pull kubespacedev/jupyter-devops:3.11
````
````
docker pull kubespacedev/jupyter-devops:3.10
````

## 3. Access to Jupyter

Visiting ``http://<hostname>:8888/?token=<token>`` in a browser loads JupyterLab, where:

- hostname is the name of the computer running Docker
- token is the secret token printed in the console.

## 4. Image build

You can run the image build with the following commands

````
git clone https://github.com/kubespace-io/napptive-applications.git
cd images/jupyter/devops
docker image build --build-arg IMAGE=jupyter/minimal-notebook:python-<VERSION> -t jupyter-devops .
````

## 5.Documentation and guides

[Jupyter Notebook](https://jupyter.org/)

[Microsoft ODBC 18](https://docs.microsoft.com/en-us/sql/connect/odbc/linux-mac/installing-the-microsoft-odbc-driver-for-sql-server?view=sql-server-2017)