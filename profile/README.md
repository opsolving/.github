# 📦 Opsolving Helm Charts

A collection of **open-source Helm charts** for widely used services and components.  
Created as community-driven alternatives after Bitnami charts moved to a commercial model.

If any chart is abandoned by the community, **Opsolving adopts and maintains it** to keep it available and up to date.

---

## 📚 Available Charts Without Good Alternatives

| Chart          | Current | Planned           |
|----------------|---------|-------------------|
| Common         | 5.X     |                   |
| EJBCA          | 9.X     |                   |
| Extra Manifest | 9.X     |                   |
| Keycloak       | 26.X    |                   |
| KeyDB          | 6.X     |                   |
| MariaDB        | 12.X    | 10.11, 11.4, 11.8 |
| Memcached      | 1.X     |                   |
| NGINX          | 1.29.X  |                   |
| phpMyAdmin     | 5.X     |                   |
| PostgreSQL     | 17      | 14, 15, 16        |
| Tomcat         | 11.X    | 9.X, 10.X         |
| WildFly        | 37.X    |                   |
| Zookeeper      | 37.X    |                   |

---

## ⚡ Google alternatives for `bitnami`

| Category     | Application          | Alternative            | Link                                                                                                                | Type      | Adopted |
|--------------|----------------------|------------------------|---------------------------------------------------------------------------------------------------------------------|-----------|---------|
| Databases    | PostgreSQL           | Percona PostgreSQL     | [percona/helm](https://github.com/percona/percona-helm-charts/tree/main/charts/pg-operator)                         | 🛠️       | ⬜       |
| Databases    | MySQL                | Percona Mysql          | [percona/helm](https://github.com/percona/percona-helm-charts/tree/main/charts/pxc-operator)                        | 🛠️       | ⬜       |
| Databases    | MongoDB              | Percona MongoDB        | [percona/helm](https://github.com/percona/percona-helm-charts/tree/main/charts/psmdb-operator)                      | 🛠️       | ⬜       |
| Databases    | CouchDB              | Apache CouchDB         | [apache/helm](https://github.com/apache/couchdb-helm/tree/main/couchdb)                                             | 📦        | ⬜       |
| Databases    | Couchbase            | Couchbase              | [couchbase/helm](https://github.com/couchbase-partners/helm-charts/tree/master/charts/couchbase-operator)           | 🛠️       | ⬜       |
| Databases    | Cassandra            | ScyllaDB               | [scylladb/helm](https://github.com/scylladb/scylla-operator/tree/master/helm)                                       | 🛠️ / 📦️ | ⬜       |
| Databases    | Redis Standalone     | Redis Operator         | [opstree/helm](https://github.com/OT-CONTAINER-KIT/redis-operator/tree/main/charts)                                 | 🛠️       | ⬜       |
| Databases    | Redis Master+Replica | Redis Operator         | [opstree/helm](https://github.com/OT-CONTAINER-KIT/redis-operator/tree/main/charts)                                 | 🛠️       | ⬜       |
| Databases    | Redis Cluster        | Redis Operator         | [opstree/helm](https://github.com/OT-CONTAINER-KIT/redis-operator/tree/main/charts)                                 | 🛠️       | ⬜       |
| Databases    | Redis Sentinel       | Redis Operator         | [opstree/helm](https://github.com/OT-CONTAINER-KIT/redis-operator/tree/main/charts)                                 | 🛠️       | ⬜       |
| Data         | Kafka                | Redpanda               | [redpanda/helm](https://github.com/redpanda-data/redpanda-operator/tree/main/charts/redpanda)                       | 📦        | ⬜       |
| Data         | Kafka                | Redpanda Operator      | [redpanda/helm](https://github.com/redpanda-data/redpanda-operator/tree/main/operator/chart)                        | 🛠️       | ⬜       |
| Data         | InfluxDB             | InfluxDB               | [influxdata/helm](https://github.com/influxdata/helm-charts/tree/master/charts)                                     | 📦        | ⬜       |
| Data         | Telegraf             | Telegraf               | [influxdata/helm](https://github.com/influxdata/helm-charts/tree/master/charts)                                     | 🛠️ / 📦  | ⬜       |
| Data         | OpenSearch           | OpenSearch             | [opensearch/helm](https://github.com/opensearch-project/helm-charts/tree/main/charts)                               | 📦        | ⬜       |
| Data         | Solr                 | Solr                   | [apache/solr](https://github.com/apache/solr-operator/tree/main/helm)                                               | 🛠️       | ⬜       |
| Networking   | External DNS         | External DNS           | [kubernetes/helm](https://github.com/kubernetes-sigs/external-dns/tree/master/charts/external-dns)                  | ⚙️        | ⬜       |
| Networking   | Consul               | Consul (HashiCrop)     | [hashicorp/helm](https://github.com/hashicorp/consul-k8s/tree/main/charts/consul)                                   | 📦        | ⬜       |
| Networking   | Kong                 | Kong                   | [kong/helm](https://github.com/Kong/charts/tree/main/charts)                                                        | 🛠️ / 📦  | ⬜       |
| Identity     | Cert Manager         | Cert Manager           | [cert-manager/helm](https://github.com/cert-manager/cert-manager/tree/master/deploy/charts/cert-manager)            | ⚙️        | ⬜       |
| Identity     | Vault                | Vault (HashiCrop)      | [hashicorp/helm](https://github.com/hashicorp/vault-helm)                                                           | 📦        | ⬜       |
| Applications | Argo CD              | Argo CD                | [argo/helm](https://github.com/argoproj/argo-helm/tree/main/charts/argo-cd)                                         | ⚙️        | ⬜       |
| Applications | Argo Workflows       | Argo Workflows         | [argo/helm](https://github.com/argoproj/argo-helm/tree/main/charts/argo-workflows)                                  | ⚙️        | ⬜       |
| Applications | Nominatim            | RobJuz Nominatim `(1)` | [robjuz/helm](https://github.com/robjuz/helm-charts/tree/master/charts/nominatim)                                   | 📦        | ⬜       |
| Applications | Jenkins              | Jenkins                | [jenkinsci/helm](https://github.com/jenkinsci/helm-charts/tree/main/charts/jenkins)                                 | ⚙️        | ⬜       |
| Applications | SonarQube            | SonarQube              | [sonarsource/helm](https://github.com/SonarSource/helm-chart-sonarqube/tree/master/charts)                          | 📦        | ⬜       |
| Applications | Airflow              | Apache Airflow         | [apache/helm](https://github.com/apache/airflow/tree/main/chart)                                                    | 📦        | ⬜       |
| Applications | Flink                | Apache Flink `(2)`     | [apache/helm](https://github.com/apache/flink-kubernetes-operator)                                                  | 🛠️       | ⬜       |
| Applications | Logstash/Elastic/..  | Elastic                | [elastic/helm](https://www.elastic.co/docs/deploy-manage/deploy/cloud-on-k8s/managing-deployments-using-helm-chart) | 🛠️       | ⬜       |
| Applications | Kiali                | Kiali                  | [kiali/helm](https://kiali.io/docs/installation/installation-guide/install-with-helm/)                              | 🛠️ / 📦  | ⬜       |
| Applications | Jaeger               | Jaeger                 | [influxdb/helm](https://github.com/jaegertracing/helm-charts/tree/main/charts)                                      | 🛠️ / 📦  | ⬜       |

- `(1)` - bitnami/postgresql dependency
- `(2)` - limited, not all configurations can be set as desired.

---

## ✅ Adoption Policy

If any chart is abandoned by the community, **Opsolving adopts and actively maintains it** to ensure stability,
availability, and long-term support.

---

### 🔑 Legend

- 🛠️ Operator
- ⚙️ Controller
- 📦 Deployment
- ⬜ Planned adoption (if abandoned by community)
- ☑️ Adopted by Opsolving (active maintenance)

---

## 🎯 Goal

This repository keeps a set of free and accessible Helm charts for commonly used services.  
The aim is to guarantee continuity, stability, and availability for the open-source ecosystem.
