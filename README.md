# NAPPTIVE applications

[![Grafana](https://github.com/kubespace-io/napptive-applications/actions/workflows/grafana-actions.yml/badge.svg)](https://github.com/kubespace-io/napptive-applications/actions/workflows/grafana-actions.yml)
[![Planka](https://github.com/kubespace-io/napptive-applications/actions/workflows/planka-actions.yml/badge.svg)](https://github.com/kubespace-io/napptive-applications/actions/workflows/planka-actions.yml)
[![n8n](https://github.com/kubespace-io/napptive-applications/actions/workflows/n8n-actions.yml/badge.svg)](https://github.com/kubespace-io/napptive-applications/actions/workflows/n8n-actions.yml)
[![DokuWiki](https://github.com/kubespace-io/napptive-applications/actions/workflows/dokuwiki-actions.yml/badge.svg)](https://github.com/kubespace-io/napptive-applications/actions/workflows/dokuwiki-actions.yml)
[![MinIO](https://github.com/kubespace-io/napptive-applications/actions/workflows/minio-actions.yml/badge.svg)](https://github.com/kubespace-io/napptive-applications/actions/workflows/minio-actions.yml)
[![Keycloak](https://github.com/kubespace-io/napptive-applications/actions/workflows/keycloak-actions.yml/badge.svg)](https://github.com/kubespace-io/napptive-applications/actions/workflows/keycloak-actions.yml)
[![Redmine](https://github.com/kubespace-io/napptive-applications/actions/workflows/redmine-actions.yml/badge.svg)](https://github.com/kubespace-io/napptive-applications/actions/workflows/redmine-actions.yml)
[![Nextcloud](https://github.com/kubespace-io/napptive-applications/actions/workflows/nextcloud-actions.yml/badge.svg)](https://github.com/kubespace-io/napptive-applications/actions/workflows/nextcloud-actions.yml)

Currently, this repository is exclusively maintained by [davma.io](https://github.com/davma-io)

## Repository purpose

1. Increase the catalog of applications that can be deployed from the [Napptive Playground](https://playground.napptive.dev/).

2. Maintain updated [OAM components](./applications/) for open source application deployment for the platform.

## Requirements

To deploy the components of this repository you will need an account on the [Napptive platform](https://napptive.com/). You can deploy the applications, configured in this repository, directly from the platform catalog.

Please note that some of the configured deployments require resources on the platform limited to a paid account. 
All applications are configured with a basic deployment, for testing purposes, capable of deploying to the free account.

## Limitations

Please note all of the following:

Initially the application deployment configurations listed in this repository for the [Napptive platform](https://napptive.com/) are designed exclusively for test environments. Eventually configurations for data persistence have been added in some applications.

Please note that if you use these applications for production environments, you are solely responsible in case of data loss. Always use data persistence, modify the resource limit of the preconfigured applications according to your needs.

At the moment none of the applications are configured to scale in high demand environments.

## References
* https://docs.napptive.com/
* https://kubevela.io/docs/
* https://github.com/napptive-actions/catalog-push-action

## Contact Support

- Organization's email: [info@kubespace.io](mailto:info@kubespace.io)
- Owner email: [contact@davma.io](mailto:contact@davma.io)
- Slack: [kubespace.io](https://join.slack.com/t/kubespaceio/shared_invite/zt-1twwd0egh-L8Hz1qz__BJXPQqOUdy3JA)

<img src="https://raw.githubusercontent.com/kubespace-io/.github/main/resources/images/kubespace.io-logo-black.png" width="600"/>