# Planka

Planka is a free open source kanban board for workgroups.

__Important__: Before deployment the application, you must modify the environment variable BASE_URL for your access url 
```
https://<nameapp>-<id-namespace>.apps.playground.napptive.dev
#example: https://kubespace-planka-cd6maeyfdrt9o3ctk9m470.apps.playground.napptive.dev
```
If you don't do this before deployment Planka won't be accessible.

You can get the __id-namespace__ with the following command:
```
playground env list
```

</br>

<img src="https://raw.githubusercontent.com/plankanban/planka/master/demo.gif" alt="drawing" width="800"/>

</br>

[![Planka](https://github.com/kubespace-io/napptive-applications/actions/workflows/planka-actions.yml/badge.svg)](https://github.com/kubespace-io/napptive-applications/actions/workflows/planka-actions.yml)

Deployment in the catalog and configuration and in some cases the container image is maintained and updated by [davma.io](mailto:contact@davma.io). 

 __This version of the application is designed for SMALL PRODUCTION ENVIRONMENTS__ . Data persistence only, not configured to scale in high-demand production environments. You can change before deploying the resource limit if you need to increase resources for your project.  

__ATTENTION Before performing the deployment you must deploy the storage component for data persistence with the STORAGE tag__. 

For more information, help or specific deployments you can contact [here](mailto:contact@davma.io).

## How to access to Planka

Once the application has been deployed, open the public endpoint navigating through the web UI to select the application, selecting the kubespace-planka component, and clicking on the associated Endpoint. Alternatively with the CLI use:

```
playground apps open kubespace-planka
```

The kubespace-planka instance automatically gets a public URL in the form of:

```
https://kubespace-planka-<id-namespace>.apps.playground.napptive.dev
```

You can get the full link in endpoints inside component kubespace-planka

## Minimal resources available
The following resources need to be available in your environment for a successful deployment:
- 1.25 cores available
- 2560 Mb of ram available

## References
* https://planka.app
* https://github.com/plankanban/planka
* https://docs.planka.cloud

## Contact Support

- Organization's email: [info@kubespace.io](mailto:info@kubespace.io)
- Owner email: [contact@davma.io](mailto:contact@davma.io)
- Slack: [kubespace.io](https://join.slack.com/t/kubespaceio/shared_invite/zt-1twwd0egh-L8Hz1qz__BJXPQqOUdy3JA)

</br>
</br>
</br>

<img src="https://raw.githubusercontent.com/kubespace-io/.github/main/resources/images/kubespace.io-logo-white.png" alt="drawing" width="400"/> 

</br>
</br>
</br>