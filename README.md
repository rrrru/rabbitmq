## Environment Variables

To run this project, you will need to add the following environment variables to github project secrets section **/settings/secrets/actions**

| Key| Value| Description|
| :-------- | :-----------| :--------------------------------|
| `DO_TOKEN`| `xxxx`| **Required**. DigitalOcean api token |
| `DO_CLUSTER_NAME ` | `dd-game` | **Required**. k8s cluster name on DigitalOcean |
| `K8S_NAMESPACE`| `rabbitmq`| **Required**. Namespace on k8s where the cluster will be deployed |
