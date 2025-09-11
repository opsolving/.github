# 📦 Opsolving Helm Charts

Community‑maintained, **open-source Helm charts** for widely used services and components.  
Born as community-driven alternatives after Bitnami charts moved to a commercial model.

If any chart is abandoned by the community, **Opsolving adopts and maintains it** to keep it available and up to date.

[![Repo: charts](https://img.shields.io/badge/Repo-charts-2b3137?logo=github)](https://github.com/opsolving/charts)
[![Helm v3](https://img.shields.io/badge/Helm-v3-0f1689?logo=helm&logoColor=white)](https://helm.sh)

---

## 📚 [Available Helm Charts](https://github.com/opsolving/charts)

### Base Charts

| Chart                                                                                    | Current |
|------------------------------------------------------------------------------------------|---------|
| [Common](https://github.com/opsolving/charts/tree/main/opsolving/common)                 | 2.31.4  |
| [Extra Manifest](https://github.com/opsolving/charts/tree/main/opsolving/extra-manifest) | 1.0.0   |

---

## ⚡ Open‑Source Alternatives for Services

| Category   | Application            | Alternative                                                                                                         | Link      |
|------------|------------------------|---------------------------------------------------------------------------------------------------------------------|-----------|
| Cache      | Redis (Cluster)        | [opstree/helm](https://github.com/OT-CONTAINER-KIT/redis-operator/tree/main/charts)                                 | 🛠️       |
|            | Redis (Master/Replica) | [opstree/helm](https://github.com/OT-CONTAINER-KIT/redis-operator/tree/main/charts)                                 | 🛠️       |
|            | Redis (Sentinel)       | [opstree/helm](https://github.com/OT-CONTAINER-KIT/redis-operator/tree/main/charts)                                 | 🛠️       |
|            | Redis (Standalone)     | [opstree/helm](https://github.com/OT-CONTAINER-KIT/redis-operator/tree/main/charts)                                 | 🛠️       |
| CI/CD      | Argo CD                | [argo/helm](https://github.com/argoproj/argo-helm/tree/main/charts/argo-cd)                                         | ⚙️        |
|            | Argo Workflows         | [argo/helm](https://github.com/argoproj/argo-helm/tree/main/charts/argo-workflows)                                  | ⚙️        |
|            | Jenkins                | [jenkinsci/helm](https://github.com/jenkinsci/helm-charts/tree/main/charts/jenkins)                                 | 📦        |
| Database   | Couchbase              | [couchbase/helm](https://github.com/couchbase-partners/helm-charts/tree/master/charts/couchbase-operator)           | 🛠️       |
|            | CouchDB                | [apache/helm](https://github.com/apache/couchdb-helm/tree/main/couchdb)                                             | 📦        |
|            | MongoDB                | [percona/helm](https://github.com/percona/percona-helm-charts/tree/main/charts/psmdb-operator)                      | 🛠️       |
|            | MySQL                  | [percona/helm](https://github.com/percona/percona-helm-charts/tree/main/charts/pxc-operator)                        | 🛠️       |
|            | PostgreSQL             | [percona/helm](https://github.com/percona/percona-helm-charts/tree/main/charts/pg-operator)                         | 🛠️       |
|            | ScyllaDB               | [scylladb/helm](https://github.com/scylladb/scylla-operator/tree/master/helm)                                       | 🛠️ / 📦️ |
| Dev Tools  | SonarQube              | [sonarsource/helm](https://github.com/SonarSource/helm-chart-sonarqube/tree/master/charts)                          | 📦        |
| Geospatial | Nominatim              | [robjuz/helm](https://github.com/robjuz/helm-charts/tree/master/charts/nominatim)                                   | 📦        |
| Gateway    | Kong                   | [kong/helm](https://github.com/Kong/charts/tree/main/charts)                                                        | 🛠️ / 📦  |
| Logging    | Elastic Stack (ECK)    | [elastic/helm](https://www.elastic.co/docs/deploy-manage/deploy/cloud-on-k8s/managing-deployments-using-helm-chart) | 🛠️       |
|            | OpenSearch             | [opensearch/helm](https://github.com/opensearch-project/helm-charts/tree/main/charts)                               | 📦        |
| Mesh       | Consul                 | [hashicorp/helm](https://github.com/hashicorp/consul-k8s/tree/main/charts/consul)                                   | 📦        |
| Mesh       | Istio                  | [istio/helm](https://github.com/istio/istio/tree/master/manifests/charts)                                           | ⚙️        |
|            | Kiali                  | [kiali/helm](https://kiali.io/docs/installation/installation-guide/install-with-helm/)                              | 🛠️ / 📦  |
| Metrics    | InfluxDB               | [influxdata/helm](https://github.com/influxdata/helm-charts/tree/master/charts)                                     | 📦        |
|            | Telegraf               | [influxdata/helm](https://github.com/influxdata/helm-charts/tree/master/charts)                                     | 🛠️ / 📦  |
| Networking | External DNS           | [kubernetes/helm](https://github.com/kubernetes-sigs/external-dns/tree/master/charts/external-dns)                  | ⚙️        |
| Search     | Apache Solr            | [apache/solr](https://github.com/apache/solr-operator/tree/main/helm)                                               | 🛠️       |
| Security   | Vault                  | [hashicorp/helm](https://github.com/hashicorp/vault-helm)                                                           | 📦        |
|            | cert-manager           | [cert-manager/helm](https://github.com/cert-manager/cert-manager/tree/master/deploy/charts/cert-manager)            | ⚙️        |
| Streaming  | Redpanda               | [redpanda/helm](https://github.com/redpanda-data/redpanda-operator/tree/main/charts/redpanda)                       | 📦        |
|            | Redpanda Operator      | [redpanda/helm](https://github.com/redpanda-data/redpanda-operator/tree/main/operator/chart)                        | 🛠️       |
| Tracing    | Jaeger                 | [jaeger/helm](https://github.com/jaegertracing/helm-charts/tree/main/charts)                                        | 🛠️ / 📦  |
| Streaming  | Flink                  | [apache/helm](https://github.com/apache/flink-kubernetes-operator)                                                  | 🛠️       |
| Scheduler  | Airflow                | [apache/helm](https://github.com/apache/airflow/tree/main/chart)                                                    | 📦        |

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
