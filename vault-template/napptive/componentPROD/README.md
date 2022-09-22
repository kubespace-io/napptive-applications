# Vault

Deployment in the catalog and configuration and in some cases the container image is maintained and updated by [davma.io](mailto:contact@davma.io)

</br>

<img src="https://www.datocms-assets.com/2885/1542059843-vaultshare-imglogo-w-stack-graphic1200x630.png" alt="drawing" width="550"/>

</br>

## HashiCorp Vault

Identity-based secrets and encryption management system

 __This version of the application is designed for PRODUCTION ENVIRONMENTS__.  

__ATTENTION Before performing the deployment you must deploy the storage component for data persistence with the STORAGE tag__.  

For more information, help or specific deployments you can contact [here](mailto:contact@davma.io).

It is not possible to deploy this version with a free Napptive account

[![Build and push images](https://github.com/davma-io-images/vault-ui/actions/workflows/docker-image.yml/badge.svg)](https://github.com/davma-io-images/vault-ui/actions/workflows/docker-image.yml)
[![Update Vault in to Napptive Playground](https://github.com/davma-io-templates/napptive-template/actions/workflows/vault-actions.yml/badge.svg)](https://github.com/davma-io-templates/napptive-template/actions/workflows/vault-actions.yml)
[![Docker Pulls](https://img.shields.io/docker/pulls/davma/vault-ui?logo=docker&logoColor=white)](https://hub.docker.com/r/davma/vault-ui)


## How to access to Vault

Once the application has been deployed, open the public endpoint navigating through the web UI to select the application, selecting the davmaio-wikijs component, and clicking on the associated Endpoint. Alternatively with the CLI use:

```
playground apps open davmaio-Vault
```

The davmaio-Vault instance automatically gets a public URL in the form of:

```
https://davmaio-vault-<active-namespace>.apps.playground.napptive.dev/ui
```

You can get the full link in endpoints inside component davmaio-vault

Once the Vault UI has loaded, you should:

- Select the number of keys needed to unlock the vault.
- Download the json file with the keys.

Now you can access to unlock the vault

__You can access the most complete training on the [HashiCorp Vault website](https://learn.hashicorp.com/collections/vault/getting-started-ui)__


## Minimal resources available
The following resources need to be available in your environment for a successful deployment:
- 0.5 of cores available
- 500 Mb of ram available

## References
* https://www.vaultproject.io/docs
* https://learn.hashicorp.com/vault
* https://learn.hashicorp.com/collections/vault/getting-started-ui



</br>
</br>
</br>

![https://github.com/davma-io](https://davma.io/wp-content/uploads/2022/05/davma.io6_-e1659187814635.png)
</br>
</br>
</br>