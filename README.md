[![GitHub license](https://img.shields.io/github/license/caprisys/helm-charts.svg)](https://github.com/caprisys/helm-charts/blob/main/LICENSE)

# helm-charts
Helm charts for various public projects

* [ElasticHQ](https://github.com/ElasticHQ/elasticsearch-HQ): there is currently no official chart
* [Kivitendo](https://github.com/kivitendo/kivitendo-erp): there is currently no official chart
* [Passless Operator](https://github.com/wavesoftware/passless-operator): there is currently no official chart
* [Percona Operator for MySQL](https://github.com/percona/percona-helm-charts/tree/main/charts/ps-operator): there is an official chart (see link), but it works only for namespaced deployments
* [Cert-Manager ClouDNS DNS01 Provider](https://github.com/mschirrmeister/cert-manager-webhook-cloudns/tree/master/deploy/cert-manager-webhook-cloudns): there is an official chart (see link), but it does not allow to restrict securityContext settings
* [kube-oidc-proxy](https://github.com/TremoloSecurity/kube-oidc-proxy/tree/master/deploy/charts/kube-oidc-proxy): there is an official chart (see link), but it does not allow to restrict securityContext settings
* Sealed Secrets: deprecated

## Installing Charts from this Repository

Add the repository to helm:

```
helm repo add caprisys https://caprisys.github.io/helm-charts/
```

Install a chart:

```
helm install caprisys/passless-operator
```
