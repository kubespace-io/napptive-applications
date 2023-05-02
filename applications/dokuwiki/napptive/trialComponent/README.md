# DokuWiki

DokuWiki is a simple to use and highly versatile Open Source wiki software that doesn't require a database. 

</br>

<img src="https://www.dokuwiki.org/_media/template:dokuwiki_template.png" alt="drawing" width="600"/> 

</br>

[![DokuWiki](https://github.com/kubespace-io/napptive-applications/actions/workflows/dokuwiki-actions.yml/badge.svg)](https://github.com/kubespace-io/napptive-applications/actions/workflows/dokuwiki-actions.yml)

This application is for development only, it is strongly recommended not to use it in production environments. It is not deployed with data persistence. __Deploy the latest version for data persistence__. 

Deployment in the catalog and configuration and in some cases the container image is maintained and updated by [davma.io](mailto:contact@davma.io)

For more information, help or specific deployments you can contact [here](mailto:contact@davma.io).


## How to access to DokuWiki

Once the application has been deployed, open the public endpoint navigating through the web UI to select the application, selecting the dokuwiki component, and clicking on the associated Endpoint. Alternatively with the CLI use:

```
playground apps open kubespace-dokuwiki
```

The kubespace-dokuwiki instance automatically gets a public URL in the form of:
```
https://kubespace-dokuwiki-<id-namespace>.apps.playground.napptive.dev
```
You can get the full link in endpoints inside component kubespace-dokuwiki.

## Admin user and first login
The default credentials are:
- User: admin
- Password: admin

Note: Please remember to change the user/password for the instance. To change credentials

## Minimal resources available
The following resources need to be available in your environment for a successful deployment:
- 0.2 cores available
- 256 MB of ram available

## References
* https://www.dokuwiki.org/dokuwiki
* https://www.dokuwiki.org/install

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