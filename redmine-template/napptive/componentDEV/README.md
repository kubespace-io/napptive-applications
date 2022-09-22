# Redmine-test

Deployment in the catalog and configuration and in some cases the container image is maintained and updated by [davma.io](mailto:contact@davma.io)

</br>

<img src="https://upload.wikimedia.org/wikipedia/commons/8/80/Redmine_logo_v1.png" alt="drawing" width="600"/>

Redmine is a flexible project management web application. Written using the Ruby on Rails framework, it is cross-platform and cross-database.

[![Update Redmine in to Napptive Playground](https://github.com/davma-io-templates/napptive-template/actions/workflows/redmine-actions.yml/badge.svg)](https://github.com/davma-io-templates/napptive-template/actions/workflows/redmine-actions.yml)

This application is for development only, it is strongly recommended not to use it in production environments. It is not deployed with data persistence. __Deploy the latest version for data persistence__. 

For more information, help or specific deployments you can contact [here](mailto:contact@davma.io).

## How to access to Redmine

Once the application has been deployed, open the public endpoint navigating through the web UI to select the application, selecting the davmaio-wikijs component, and clicking on the associated Endpoint. Alternatively with the CLI use:

```
playground apps open davmaio-redmine
```

The davmaio-redmine instance automatically gets a public URL in the form of:

```
https://davmaio-redmine-<active-namespace>.apps.playground.napptive.dev
```

You can get the full link in endpoints inside component davmaio-wikijs

## Admin user and first login
The default credentials are:
- User: admin
- Password: admin

Note: Please remember to change the user/password for the instance. To change credentials

## Minimal resources available
The following resources need to be available in your environment for a successful deployment:
- 1.5 of cores available
- 1.5 GB of ram available

## References
* https://www.redmine.org/
* https://www.redmine.org/projects/redmine/wiki/Guide

## Support Contact

- Email: [contact@davma.io](mailto:contact@davma.io)
- Slack: [davma.io](https://join.slack.com/t/davmaioespacio/shared_invite/zt-1ad2hnzn6-DdMBvCaOPozfVAHhzvlSVQ)

</br>
</br>
</br>

![https://github.com/davma-io](https://davma.io/wp-content/uploads/2022/05/davma.io6_-e1659187814635.png)
</br>
</br>
</br>










<!--    

        playground login --patFile D:/Github/no-git/napptive-cli/test_pat.dat
        kubectl --kubeconfig napptive-cli/napptive-kubeconfig create -f napptive-n8n/component/

        playground catalog push davma-io/n8n:v1.0 napptive-n8n/component/
        playground catalog remove davma-io/n8n:v1.
        
-->