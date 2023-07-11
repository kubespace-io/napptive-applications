# Nextcloud

Nextcloud is the most popular on-premises content collaboration platform you can download.

</br>

![https://github.com/kubespace-io](https://nextcloud.com/media/Nextcloud_Hub_background.png)

[![Nextcloud](https://github.com/kubespace-io/napptive-applications/actions/workflows/nextcloud-actions.yml/badge.svg)](https://github.com/kubespace-io/napptive-applications/actions/workflows/nextcloud-actions.yml)

Deployment in the catalog and configuration and in some cases the container image is maintained and updated by [davma.io](mailto:contact@davma.io).

This application is for development only, it is strongly recommended not to use it in production environments. It is not deployed with data persistence. __Deploy the standard version for data persistence__. 

For more information, help or specific deployments you can contact [here](mailto:contact@davma.io).

## How to access to Nextcloud

Once the application has been deployed, open the public endpoint navigating through the web UI to select the application, selecting the kubespace-nextcloud component, and clicking on the associated Endpoint. Alternatively with the CLI use:

```
playground apps open kubespace-nextcloud
```

The kubespace-nextcloud instance automatically gets a public URL in the form of:

```
https://kubespace-nextcloud-<active-namespace>.apps.playground.napptive.dev
```

You can get the full link in endpoints inside component kubespace-nextcloud

## Minimal resources available
The following resources need to be available in your environment for a successful deployment:
- 1.5 cores available
- 3072 Mb of ram available

## References
* https://nextcloud.com/
* https://nextcloud.com/support/
* https://docs.nextcloud.com/server/latest/admin_manual/contents.html

## Contact Support

- Organization's email: [info@kubespace.io](mailto:info@kubespace.io)
- Owner email: [contact@davma.io](mailto:contact@davma.io)
- Slack: [kubespace.io](https://join.slack.com/t/kubespaceio/shared_invite/zt-1twwd0egh-L8Hz1qz__BJXPQqOUdy3JA)

</br>
</br>
</br>

<img src="https://raw.githubusercontent.com/kubespace-io/.github/main/resources/images/kubespace.io-logo-white.png" alt="drawing" width="400"/> 