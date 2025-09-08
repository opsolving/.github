# 📦 Opsolving Helm Charts

A collection of **open-source Helm charts** for widely used services and components.  
Created as community-driven alternatives after Bitnami charts moved to a commercial model.  

If any chart is abandoned by the community, **Opsolving adopts and maintains it** to keep it available and up to date.  

---

## 📚 Available Charts

| Chart         | Current | Planned           |
|---------------|---------|-------------------|
| Redis         | 8.X     | 7.X               |
| Redis Cluster | 8.X     | 7.X               |
| EJBCA         | 9.X     |                   |
| Kafka         | 4.X     | 3.X               |
| Keycloak      | 26.X    |                   |
| KeyDB         | 6.X     |                   |
| Logstash      | 9.X     | 8.X               |
| MariaDB       | 12.X    | 10.11, 11.4, 11.8 |
| Memcached     | 1.X     |                   |
| NGINX         | 1.29.X  |                   |
| phpMyAdmin    | 5.X     |                   |
| Tomcat        | 11.X    | 9.X, 10.X         |
| WildFly       | 37.X    |                   |
| PostgreSQL    | 17      | 14, 15, 16        |
| Zookeeper     | 37.X    |                   |

---

## ⚡ Alternatives

| Category      | Bitnami Chart   | Alternative            | Link                                                                 | Type | Adopted |
|---------------|-----------------|------------------------|----------------------------------------------------------------------|------|------------|
| Databases     | PostgreSQL      | Percona PostgreSQL     | [percona-helm-charts/pg-operator](https://github.com/percona/percona-helm-charts/tree/main/charts/pg-operator) | 🛠️ | ⬜ |
| Databases     | MySQL           | Percona XtraDB Cluster | [percona-helm-charts/pxc-operator](https://github.com/percona/percona-helm-charts/tree/main/charts/pxc-operator) | 🛠️ | ⬜ |
| Databases     | MongoDB         | Percona MongoDB        | [percona-helm-charts/psmdb-operator](https://github.com/percona/percona-helm-charts/tree/main/charts/psmdb-operator) | 🛠️ | ⬜ |
| Databases     | CouchDB         | Official Apache CouchDB         | [apache/couchdb-helm](https://github.com/apache/couchdb-helm/tree/main/couchdb) | 📦 | ⬜ |
| Databases     | Couchbase       | Official Couchbase              | [couchbase-partners/helm-charts/couchbase-operator](https://github.com/couchbase-partners/helm-charts/tree/master/charts/couchbase-operator) | 🛠️ | ⬜ |
| Databases     | ScyllaDB        | Official ScyllaDB              | [scylladb/scylla-operator](https://github.com/scylladb/scylla-operator/tree/master/helm) | 🛠️ | ⬜ |
| Databases     | Redis           | Redis from Opstree     | [OT-CONTAINER-KIT/redis-operator](https://github.com/OT-CONTAINER-KIT/redis-operator/tree/main/charts/redis-operator) | 🛠️ | ⬜ |
| Data          | Kafka           | Official Redpanda      | [redpanda-operator/charts/redpanda](https://github.com/redpanda-data/redpanda-operator/tree/main/charts/redpanda) | ⚙️ | ⬜ |
| Data          | Kafka           | Official Redpanda      | [redpanda-operator/operator/chart](https://github.com/redpanda-data/redpanda-operator/tree/main/operator/chart) | 🛠️ | ⬜ |
| Data          | InfluxDB        | Official InfluxDB      | [influxdata/helm-charts](https://github.com/influxdata/helm-charts) | 📦 | ⬜ |
| Data          | OpenSearch      | Official OpenSearch    | [opensearch-project/helm-charts](https://github.com/opensearch-project/helm-charts/tree/main/charts) | 📦 | ⬜ |
| Data          | Solr            | Solr                  | [apache/solr-operator](https://github.com/apache/solr-operator/tree/main/helm) | 🛠️ | ⬜ |
| Networking    | External DNS    | Official External DNS   | [kubernetes-sigs/external-dns](https://github.com/kubernetes-sigs/external-dns/tree/master/charts/external-dns) | ⚙️ | ⬜ |
| Networking    | Consul          | Official Consul (HashiCrop)     | [hashicorp/consul-k8s](https://github.com/hashicorp/consul-k8s/tree/main/charts/consul) | 📦 | ⬜ |
| Networking    | Kong            | Official Kong                  | [Kong/charts](https://github.com/Kong/charts/tree/main/charts) | 📦 | ⬜ |
| Identity      | Cert Manager    | Official Cert Manager           | [cert-manager/cert-manager](https://github.com/cert-manager/cert-manager/tree/master/deploy/charts/cert-manager) | ⚙️ | ⬜ |
| Identity      | Vault           | Official Vault (HashiCrop)               | [hashicorp/vault-helm](https://github.com/hashicorp/vault-helm) | 📦 | ⬜ |
| Applications  | Argo CD         | Official Argo CD                | [argo-helm/argo-cd](https://github.com/argoproj/argo-helm/tree/main/charts/argo-cd) | ⚙️ | ⬜ |
| Applications  | Argo Workflows  | Official Argo Workflows         | [argo-helm/argo-workflows](https://github.com/argoproj/argo-helm/tree/main/charts/argo-workflows) | ⚙️ | ⬜ |
| Applications  | Nominatim       | Nominatim              | [robjuz/helm-charts/nominatim](https://github.com/robjuz/helm-charts/tree/master/charts/nominatim) | 📦 | ⬜ |
| Applications  | Jenkins         | Official Jenkins               | [jenkinsci/helm-charts](https://github.com/jenkinsci/helm-charts/tree/main/charts/jenkins) | 📦 | ⬜ |
| Applications  | SonarQube       | Official SonarQube             | [SonarSource/helm-chart-sonarqube](https://github.com/SonarSource/helm-chart-sonarqube/tree/master/charts) | 📦 | ⬜ |

---

## ✅ Adoption Policy

If any chart is abandoned by the community, **Opsolving adopts and actively maintains it** to ensure stability, availability, and long-term support.

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
