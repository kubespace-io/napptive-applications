# Keycloak

Keycloak is a Open Source Identity and Access Management.

</br>

<img src="https://www.keycloak.org/resources/images/screen-login.png" alt="drawing" width="600"/>

[![Update Keycloak in to Napptive Playground](https://github.com/davma-io-templates/napptive-template/actions/workflows/keycloak-actions.yml/badge.svg)](https://github.com/davma-io-templates/napptive-template/actions/workflows/keycloak-actions.yml)

This application is for development only, it is strongly recommended not to use it in production environments. It is not deployed with data persistence. __Deploy the latest version for data persistence__. 

Deployment in the catalog and configuration and in some cases the container image is maintained and updated by [davma.io](mailto:contact@davma.io)

For more information, help or specific deployments you can contact [here](mailto:contact@davma.io).


## How to access to Keycloak

Once the application has been deployed, open the public endpoint navigating through the web UI to select the application, selecting the keycloak component, and clicking on the associated Endpoint. Alternatively with the CLI use:

```
playground apps open kubespace-keycloak
```

The kubespace-keycloak instance automatically gets a public URL in the form of:
```
https://kubespace-keycloak-<active-namespace>.apps.playground.napptive.dev/admin/master/console
```
You can get the full link in endpoints inside component kubespace-keycloak.

## Admin user and first login
The default credentials are:
- User: admin
- Password: admin

Note: Please remember to change the user/password for the instance. To change credentials

## Minimal resources available
The following resources need to be available in your environment for a successful deployment:
- 1.750 cores available
- 2560 MB of ram available

## References
* https://www.keycloak.org/
* https://www.keycloak.org/documentation

## Contact Support

- Organization's email: [info@kubespace.io](mailto:info@kubespace.io)
- Owner email: [contact@davma.io](mailto:contact@davma.io)
- Slack: [kubespace.io](https://join.slack.com/t/kubespaceio/shared_invite/zt-1twwd0egh-L8Hz1qz__BJXPQqOUdy3JA)

</br>
</br>
</br>

<img src="https://raw.githubusercontent.com/kubespace-io/.github/main/resources/images/kubespace.io-logo-white.png" alt="drawing" width="400"/> 
