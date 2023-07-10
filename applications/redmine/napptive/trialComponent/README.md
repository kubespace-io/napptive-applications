# Redmine

Redmine is a flexible project management web application. Written using the Ruby on Rails framework, it is cross-platform and cross-database.

</br>

<img src="https://upload.wikimedia.org/wikipedia/commons/8/80/Redmine_logo_v1.png" alt="drawing" width="600"/>

</br>

[![Redmine](https://github.com/kubespace-io/napptive-applications/actions/workflows/redmine-actions.yml/badge.svg)](https://github.com/kubespace-io/napptive-applications/actions/workflows/redmine-actions.yml)

This application is for development only, it is strongly recommended not to use it in production environments. It is not deployed with data persistence. __Deploy the latest version for data persistence__. 

Deployment in the catalog and configuration and in some cases the container image is maintained and updated by [davma.io](mailto:contact@davma.io)

For more information, help or specific deployments you can contact [here](mailto:contact@davma.io).

## How to access to Redmine

Once the application has been deployed, open the public endpoint navigating through the web UI to select the application, selecting the davmaio-wikijs component, and clicking on the associated Endpoint. Alternatively with the CLI use:

```
playground apps open kubespace-redmine
```

The kubespace-redmine instance automatically gets a public URL in the form of:

```
https://kubespace-redmine-<active-namespace>.apps.playground.napptive.dev
```

You can get the full link in endpoints inside component davmaio-wikijs

## Admin user and first login
The default credentials are:
- User: admin
- Password: admin

Note: Please remember to change the user/password for the instance. To change credentials

## Minimal resources available
The following resources need to be available in your environment for a successful deployment:
- 0.5 cores available
- 512 MB ram available

## References
* https://www.redmine.org/
* https://www.redmine.org/projects/redmine/wiki/Guide

## Contact Support

- Organization's email: [info@kubespace.io](mailto:info@kubespace.io)
- Owner email: [contact@davma.io](mailto:contact@davma.io)
- Slack: [kubespace.io](https://join.slack.com/t/kubespaceio/shared_invite/zt-1twwd0egh-L8Hz1qz__BJXPQqOUdy3JA)

</br>
</br>
</br>

<img src="https://raw.githubusercontent.com/kubespace-io/.github/main/resources/images/kubespace.io-logo-white.png" alt="drawing" width="400"/> 
