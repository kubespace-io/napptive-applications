# Jupiter template for NAPPTIVE

Jupiter-TensorFlow deployment with a single click in NAPPTIVE. Once registered on the platform you can deploy the application from the application catalog.

## Requirements

 - Free account on [NAPPTIVE platform](https://napptive.com/)


---


## APP Info Napptive HUB


This app will deploy a Jupyter instance with python 3.8 / 3.9 / 3.10, tensorflow and pyodbc 4.0.30 pre-installed

[![Build and push images](https://github.com/davma-io-images/jupyter-tensorflow-pyodbc/actions/workflows/docker-image.yml/badge.svg)](https://github.com/davma-io-images/jupyter-tensorflow-pyodbc/actions/workflows/docker-image.yml)

[![Update application to Napptive Playground](https://github.com/davma-io-templates/jupyter-templates/actions/workflows/jupiterTF-napptive-push.yml/badge.svg)](https://github.com/davma-io-templates/jupyter-templates/actions/workflows/jupiterTF-napptive-push.yml)

[![Docker Pulls](https://img.shields.io/docker/pulls/davma/jupyter-tensorflow-pyodbc?logo=docker&logoColor=white)](https://hub.docker.com/repository/docker/davma/jupyter-tensorflow-pyodbc)  

Jupyter Notebook is a web-based interactive computing platform.

> This application is for development only, it is strongly recommended not to use it in production environments. It is not deployed with data persistence. For more info or help [contact](mailto:contact@davma.io)



## How to access to Jupiter-TensorFlow

Once the application has been deployed, open the public endpoint navigating through the web UI to select the application, selecting the Jupyter component, and clicking on the associated Endpoint. Alternatively with the CLI use:

```
playground apps open davmaio-jupyter-tensorflow:<version>
```

The davmaio-jupyter instance automatically gets a public URL. If the application is APP_OK, copy the ingress link in your browser. 

```
https://davmaio-jupyter-<active-namespace>.apps.playground.napptive.dev
```

- We need a token to log into the page. We can obtain the token checking the application logs:


## References
* https://jupyter.org/
* https://docs.jupyter.org/en/latest/index.html
* https://hub.docker.com/r/davma/jupyter-tensorflow-pyodbc










<!--    

        playground login --patFile D:/Github/no-git/napptive-cli/test_pat.dat
        kubectl --kubeconfig napptive-cli/napptive-kubeconfig create -f napptive-jupyter-tensorflow-pyodbc/component39/

        playground catalog push davma-io/jupyter-tensorflow:v3.9 napptive-jupyter-tensorflow-pyodbc/component39/
        playground catalog push davma-io/jupyter-tensorflow:v3.8 napptive-jupyter-tensorflow-pyodbc/component38/
        playground catalog push davma-io/jupyter-tensorflow:v3.10 napptive-jupyter-tensorflow-pyodbc/component310/
        playground catalog remove davma-io/jupyter:v1.
        
-->