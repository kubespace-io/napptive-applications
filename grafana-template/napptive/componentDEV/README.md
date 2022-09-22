# Grafana-test

Deployment in the catalog and configuration and in some cases the container image is maintained and updated by [davma.io](mailto:contact@davma.io)

</br>

<img src="https://grafana.com/static/img/grafana_labs.jpg" alt="drawing" width="600"/>

Grafana - is the open source analytics & monitoring solution for every database.

[![Update Grafana in to Napptive Playground](https://github.com/davma-io-templates/napptive-template/actions/workflows/grafana-actions.yml/badge.svg)](https://github.com/davma-io-templates/napptive-template/actions/workflows/grafana-actions.yml)

This application is for development only, it is strongly recommended not to use it in production environments. It is not deployed with data persistence. __Deploy the latest version for data persistence__. 

For more information, help or specific deployments you can contact [here](mailto:contact@davma.io).


## How to access to Grafana

Once the application has been deployed, open the public endpoint navigating through the web UI to select the application, selecting the Grafana component, and clicking on the associated Endpoint. Alternatively with the CLI use:

```
playground apps open davmaio-grafana
```

The davmaio-grafana instance automatically gets a public URL in the form of:
```
https://davmaio-grafana-<active-namespace>.apps.playground.napptive.dev
```
You can get the full link in endpoints inside component davmaio-grafana.

## Admin user and first login
The default credentials are:
- User: admin
- Password: admin

Note: Please remember to change the user/password for the instance. To change credentials

## Minimal resources available
The following resources need to be available in your environment for a successful deployment:
- 0.2 of cores available
- 256 MB of ram available

## References
* https://grafana.com/
* https://grafana.com/docs/

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