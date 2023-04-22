# Minio-test

Deployment in the catalog and configuration and in some cases the container image is maintained and updated by [davma.io](mailto:contact@davma.io)

</br>

<img src="https://blog.min.io/content/images/2021/04/console_header--2-.png" alt="drawing" width="600"/>

MinIO is a High Performance Object Storage released under GNU Affero General Public License v3.0. It is API compatible with Amazon S3 cloud storage service.

[![Update Minio in to Napptive Playground](https://github.com/davma-io-templates/napptive-template/actions/workflows/minio-actions.yml/badge.svg)](https://github.com/davma-io-templates/napptive-template/actions/workflows/minio-actions.yml)

This application is for development only, it is strongly recommended not to use it in production environments. It is not deployed with data persistence. __Deploy the latest version for data persistence__. 

For more information, help or specific deployments you can contact [here](mailto:contact@davma.io).


## How to access to Minio

Once the application has been deployed, open the public endpoint navigating through the web UI to select the application, selecting the minio component, and clicking on the associated Endpoint. Alternatively with the CLI use:

```
playground apps open davmaio-minio
```

The davmaio-minio instance automatically gets a public URL in the form of:
```
https://davmaio-minio-<active-namespace>.apps.playground.napptive.dev
```
You can get the full link in endpoints inside component davmaio-minio.

## Admin user and first login
The default credentials are:
- User: davma-minio
- Password: davma-minio@

Note: Please remember to change the user/password for the instance. To change credentials

## Minimal resources available
The following resources need to be available in your environment for a successful deployment:
- 0.2 cores available
- 256 MB of ram available

## References
* https://min.io/
* https://docs.min.io/minio/baremetal/console/minio-console.html/

## Contact Support

- Email: [contact@davma.io](mailto:contact@davma.io)
- Slack: [davma.io](https://join.slack.com/t/davmaioespacio/shared_invite/zt-1ad2hnzn6-DdMBvCaOPozfVAHhzvlSVQ)

</br>
</br>
</br>

![https://github.com/davma-io](https://davma.io/wp-content/uploads/2022/05/davma.io6_-e1659187814635.png)
</br>
</br>
</br>