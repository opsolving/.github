# 📦 Opsolving Helm Charts

Community‑maintained, **open-source Helm charts** for widely used services and components.  
Born as community-driven alternatives after Bitnami charts moved to a commercial model.

If any chart is abandoned by the community, **Opsolving adopts and maintains it** to keep it available and up to date.

[![Repo: charts](https://img.shields.io/badge/Repo-charts-2b3137?logo=github)](https://github.com/opsolving/charts)
[![Helm v3](https://img.shields.io/badge/Helm-v3-0f1689?logo=helm&logoColor=white)](https://helm.sh)

---

## 📑 Table of Contents

- [Available Helm Charts](#-available-helm-charts)
- [Open‑Source Alternatives for Services](#-open-source-alternatives-for-services)
- [Adoption Policy](#-adoption-policy)
- [Legend](#-legend)
- [Using the Charts](#-using-the-charts)
- [Contributing](#-contributing)
- [Support](#-support)
- [Goal](#-goal)

---

## 📚 [Available Helm Charts](https://github.com/opsolving/charts)

### Base Charts

| Chart          | Current |
|----------------|---------|
| [Common](https://github.com/opsolving/charts/tree/main/opsolving/common)         | 2.31.4  |
| [Extra Manifest](https://github.com/opsolving/charts/tree/main/opsolving/extra-manifest) | 1.0.0   |

---

## ⚡ Open‑Source Alternatives for Services

| Category     | Application          | Alternative                                                                                                         | Link      |
|--------------|----------------------|---------------------------------------------------------------------------------------------------------------------|-----------|
| Databases    | PostgreSQL           | [percona/helm](https://github.com/percona/percona-helm-charts/tree/main/charts/pg-operator)                         | 🛠️       |
| Databases    | MySQL                | [percona/helm](https://github.com/percona/percona-helm-charts/tree/main/charts/pxc-operator)                        | 🛠️       |
| Databases    | MongoDB              | [percona/helm](https://github.com/percona/percona-helm-charts/tree/main/charts/psmdb-operator)                      | 🛠️       |
| Databases    | CouchDB              | [apache/helm](https://github.com/apache/couchdb-helm/tree/main/couchdb)                                             | 📦        |
| Databases    | Couchbase            | [couchbase/helm](https://github.com/couchbase-partners/helm-charts/tree/master/charts/couchbase-operator)           | 🛠️       |
| Databases    | ScyllaDB             | [scylladb/helm](https://github.com/scylladb/scylla-operator/tree/master/helm)                                       | 🛠️ / 📦️ |
| Databases    | Redis Standalone     | [opstree/helm](https://github.com/OT-CONTAINER-KIT/redis-operator/tree/main/charts)                                 | 🛠️       |
| Databases    | Redis Master+Replica | [opstree/helm](https://github.com/OT-CONTAINER-KIT/redis-operator/tree/main/charts)                                 | 🛠️       |
| Databases    | Redis Cluster        | [opstree/helm](https://github.com/OT-CONTAINER-KIT/redis-operator/tree/main/charts)                                 | 🛠️       |
| Databases    | Redis Sentinel       | [opstree/helm](https://github.com/OT-CONTAINER-KIT/redis-operator/tree/main/charts)                                 | 🛠️       |
| Data         | Redpanda             | [redpanda/helm](https://github.com/redpanda-data/redpanda-operator/tree/main/charts/redpanda)                       | 📦        |
| Data         | Redpanda             | [redpanda/helm](https://github.com/redpanda-data/redpanda-operator/tree/main/operator/chart)                        | 🛠️       |
| Data         | InfluxDB             | [influxdata/helm](https://github.com/influxdata/helm-charts/tree/master/charts)                                     | 📦        |
| Data         | Telegraf             | [influxdata/helm](https://github.com/influxdata/helm-charts/tree/master/charts)                                     | 🛠️ / 📦  |
| Data         | OpenSearch           | [opensearch/helm](https://github.com/opensearch-project/helm-charts/tree/main/charts)                               | 📦        |
| Data         | Solr                 | [apache/solr](https://github.com/apache/solr-operator/tree/main/helm)                                               | 🛠️       |
| Networking   | External DNS         | [kubernetes/helm](https://github.com/kubernetes-sigs/external-dns/tree/master/charts/external-dns)                  | ⚙️        |
| Networking   | Consul               | [hashicorp/helm](https://github.com/hashicorp/consul-k8s/tree/main/charts/consul)                                   | 📦        |
| Networking   | Kong                 | [kong/helm](https://github.com/Kong/charts/tree/main/charts)                                                        | 🛠️ / 📦  |
| Identity     | cert-manager         | [cert-manager/helm](https://github.com/cert-manager/cert-manager/tree/master/deploy/charts/cert-manager)            | ⚙️        |
| Identity     | Vault                | [hashicorp/helm](https://github.com/hashicorp/vault-helm)                                                           | 📦        |
| Applications | Argo CD              | [argo/helm](https://github.com/argoproj/argo-helm/tree/main/charts/argo-cd)                                         | ⚙️        |
| Applications | Argo Workflows       | [argo/helm](https://github.com/argoproj/argo-helm/tree/main/charts/argo-workflows)                                  | ⚙️        |
| Applications | Nominatim            | [robjuz/helm](https://github.com/robjuz/helm-charts/tree/master/charts/nominatim)                                   | 📦        |
| Applications | Jenkins              | [jenkinsci/helm](https://github.com/jenkinsci/helm-charts/tree/main/charts/jenkins)                                 | ⚙️        |
| Applications | SonarQube            | [sonarsource/helm](https://github.com/SonarSource/helm-chart-sonarqube/tree/master/charts)                          | 📦        |
| Applications | Airflow              | [apache/helm](https://github.com/apache/airflow/tree/main/chart)                                                    | 📦        |
| Applications | Flink                | [apache/helm](https://github.com/apache/flink-kubernetes-operator)                                                  | 🛠️       |
| Applications | Logstash/Elastic/..  | [elastic/helm](https://www.elastic.co/docs/deploy-manage/deploy/cloud-on-k8s/managing-deployments-using-helm-chart) | 🛠️       |
| Applications | Kiali                | [kiali/helm](https://kiali.io/docs/installation/installation-guide/install-with-helm/)                              | 🛠️ / 📦  |
| Applications | Jaeger               | [jaeger/helm](https://github.com/jaegertracing/helm-charts/tree/main/charts)                                        | 🛠️ / 📦  |
| Applications | Istio                | [istio/helm](https://github.com/istio/istio/tree/master/manifests/charts)                                           | ⚙️        |

---

## ✅ Adoption Policy

If any chart is abandoned by the community, **Opsolving adopts and actively maintains it** to ensure stability,
availability, and long-term support.

---

## 🔑 Legend

- 🛠️ Operator — cluster‑wide, manages an application’s lifecycle using CRDs.
- ⚙️ Controller — watches Kubernetes objects and reconciles their state to match the spec.
- 📦 Deployment — namespaced, safe deployment of an application.

---

## 🚀 Using the Charts

- Browse all charts in the `opsolving/charts` repository: https://github.com/opsolving/charts
- Each chart contains installation instructions, default values, and upgrade notes in its README.
- Base building blocks live under `opsolving/common` and `opsolving/extra-manifest`.

---

## 🤝 Contributing

Contributions are welcome! If you want to fix a bug, improve documentation, or add a new chart:

- Open an issue or a pull request in `opsolving/charts`: https://github.com/opsolving/charts
- Provide clear steps to reproduce (if reporting a bug) and keep PRs focused.

---

## 🆘 Support

This is a community-driven effort. If you need help or found a problem, please open an issue here:

- Issues: https://github.com/opsolving/charts/issues

---

## 🎯 Goal

This repository keeps a set of free and accessible Helm charts for commonly used services.  
The aim is to guarantee continuity, stability, and availability for the open-source ecosystem.
