# azure-airflow-kubernetes

This is a project that contains source code required to provision an AKS cluster with Terraform and to install Airflow
on the AKS cluster using a Helm chart.

The blogpost with further details can be found [here](https://www.fpgmaas.com/blog/azure-airflow-kubernetes).

```
.
├── Dockerfile
├── README.md
├── airflow
│   ├── pv-logs.yaml
│   ├── pvc-logs.yaml
│   └── values.yaml
├── dags
│   └── example.py
└── terraform
    ├── main.auto.tfvars
    ├── main.tf
    └── variables.tf
```
