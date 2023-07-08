# Grafana

Grafana is the open source analytics & monitoring solution for every database.

</br>

![https://github.com/kubespace-io](https://grafana.com/media/grafana/images/grafana-dashboard-english.png)

[![Grafana](https://github.com/kubespace-io/napptive-applications/actions/workflows/grafana-actions.yml/badge.svg)](https://github.com/kubespace-io/napptive-applications/actions/workflows/grafana-actions.yml) 

Deployment in the catalog and configuration and in some cases the container image is maintained and updated by [davma.io](https://github.com/davma-io)

 __This version of the application is designed for SMALL PRODUCTION ENVIRONMENTS__.  

__ATTENTION Before performing the deployment you must deploy the storage component for data persistence with the STORAGE tag__. 

For more information, help or specific deployments you can contact [here](mailto:contact@davma.io).


## How to access to Grafana

Once the application has been deployed, open the public endpoint navigating through the web UI to select the application, selecting the Grafana component, and clicking on the associated Endpoint. Alternatively with the CLI use:

```
playground apps open kubespace-grafana
```

The kubespace-grafana instance automatically gets a public URL in the form of:
```
https://kubespace-grafana-<active-namespace>.apps.playground.napptive.dev
```
You can get the full link in endpoints inside component kubespace-grafana.

## Admin user and first login
The default credentials are:
- User: admin
- Password: admin

Note: Please remember to change the user/password for the instance. To change credentials

## Minimal resources available
The following resources need to be available in your environment for a successful deployment:
- 0.5 cores available
- 1024 MB of ram available

## References
* https://grafana.com/
* https://grafana.com/docs/

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