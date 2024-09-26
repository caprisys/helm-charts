[![GitHub license](https://img.shields.io/github/license/caprisys/helm-charts.svg)](https://github.com/caprisys/helm-charts/blob/main/LICENSE)

# helm-charts
Helm charts for various public projects

* [ElasticHQ](https://github.com/ElasticHQ/elasticsearch-HQ): there is currently no official chart
* [Kivitendo](https://github.com/kivitendo/kivitendo-erp): there is currently no official chart
* [Passless Operator](https://github.com/wavesoftware/passless-operator): there is currently no official chart
* [Percona Operator for MySQL](https://github.com/percona/percona-helm-charts/tree/main/charts/ps-operator): there is an official chart (see link), but it works only for namespaced deployments

## Installing Charts from this Repository

Add the repository to helm:

```
helm repo add caprisys https://caprisys.github.io/helm-charts/
```

Install a chart:

```
helm install caprisys/passless-operator
```
