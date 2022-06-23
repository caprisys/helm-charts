[![GitHub license](https://img.shields.io/github/license/caprisys/helm-charts.svg)](https://github.com/caprisys/helm-charts/blob/main/LICENSE)

# helm-charts
Helm charts for various public projects

* [ElasticHQ](https://github.com/ElasticHQ/elasticsearch-HQ)
* [Kivitendo](https://github.com/kivitendo/kivitendo-erp)
* [Sealed Secrets](https://github.com/bitnami-labs/sealed-secrets)
* [Passless Operator](https://github.com/wavesoftware/passless-operator)

## Installing Charts from this Repository

Add the repository to helm:

```
helm repo add caprisys https://caprisys.github.io/helm-charts/
```

Install a chart:

```
helm install caprisys/passless-operator
```
