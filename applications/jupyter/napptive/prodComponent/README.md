# Jupyter

Deployment in the catalog and configuration and in some cases the container image is maintained and updated by [davma.io](mailto:contact@davma.io)

</br>

<!-- ![https://github.com/davma-io](https://conocimientolibre.mx/wp-content/uploads/2019/11/ansible-glue-tools.png) -->
<img src="https://assets.website-files.com/6141c89a3874c3702674a1c0/625012c9c0dbf1887c4bf7c7_623d8b3bd384c356fff4d0c8_memgraph-jupyter-notebook-cover.png" alt="drawing" width="600"/> 

</br> 

## This app will deploy a Jupyter instance

__Jupyter Notebook is a web-based interactive computing platform.__

[![Build jupyter-ultimate](https://github.com/davma-io-images/jupyterlab/actions/workflows/jupyter-ultimate.yml/badge.svg)](https://github.com/davma-io-images/jupyterlab/actions/workflows/jupyter-ultimate.yml)
[![Update Jupyter to Napptive Playground](https://github.com/davma-io-templates/napptive-template/actions/workflows/jupyter-actions.yml/badge.svg)](https://github.com/davma-io-templates/napptive-template/actions/workflows/jupyter-actions.yml)
[![Docker Pulls](https://img.shields.io/docker/pulls/davma/jupyter-ultimate?logo=docker&logoColor=white)](https://hub.docker.com/r/davma/jupyter-ultimate)

 __This version of the application is designed for SMALL PRODUCTION ENVIRONMENTS__ . Data persistence only, not configured to scale in high-demand production environments. You can change before deploying the resource limit if you need to increase resources for your project.  

__ATTENTION Before performing the deployment you must deploy the storage component for data persistence with the STORAGE tag__.

## Pre-installed components

This image is a modification of the official [Jupyter Notebook Deep Learning Stack](https://hub.docker.com/r/jupyter/tensorflow-notebook) image. 

The following components have been added:

CLI Components
- Azure CLI
- AWS CLI
- Napptive CLI 

Infrastructure Components
- kubectl
- Terraform
- Ansible 

Python Components
- TensorFlow
- Vault API client
- Pyodbc
- PyAudio
- pydub
- ffmpeg


## How to access to Jupyter

Once the application has been deployed, open the public endpoint navigating through the web UI to select the application, selecting the Jupyter component, and clicking on the associated Endpoint. Alternatively with the CLI use:

```
playground apps open davmaio-jupyter
```

The davmaio-jupyter instance automatically gets a public URL. If the application is APP_OK, copy the ingress link in your browser. 

```
https://davmaio-jupyter-<active-namespace>.apps.playground.napptive.dev
```

- We need a token to log into the page. We can obtain the token checking the application logs:


## References
* https://jupyter.org/
* https://docs.ansible.com/
* https://www.terraform.io/intro
* https://docs.jupyter.org/en/latest/index.html

</br>
</br>
</br>

![https://github.com/davma-io](https://davma.io/wp-content/uploads/2022/05/davma.io6_-e1659187814635.png)
</br>
</br>
</br>