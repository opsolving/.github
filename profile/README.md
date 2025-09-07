# 📦 Opsolving Helm Charts

A collection of **open-source Helm charts** for widely used services and components.  
Created as community-driven alternatives after Bitnami charts moved to a commercial model.  

If any chart is abandoned by the community, **Opsolving adopts and maintains it** to keep it available and up to date.  

---

## 📚 Available Charts

<table>
<tr>
<td valign="top">

### 🗄️ Databases
🐘 PostgreSQL<br>🐬 MySQL<br>🍃 MongoDB<br>🔴 Redis<br>🔴 Redis Cluster<br>🗂️ phpMyAdmin

</td>
<td valign="top">

### 📡 Data & Streaming
📊 Kafka<br>📡 Zookeeper<br>📥 Logstash<br>🐇 RabbitMQ<br>🦊 Redpanda

</td>
<td valign="top">

### 🔐 Identity & Web
🦄 Keycloak<br>🔑 KeyDB<br>☕ Tomcat<br>🧩 WildFly<br>🗄️ OpenLDAP<br>📜 EJBCA

</td>
</tr>
</table>

---

## ⚡ Alternatives

| Category      | Chart           | Alternative            | Link                                                                 | Type | Adopted |
|---------------|-----------------|------------------------|----------------------------------------------------------------------|------|------------|
| Databases     | PostgreSQL      | Percona PostgreSQL     | [percona-helm-charts/pg-operator](https://github.com/percona/percona-helm-charts/tree/main/charts/pg-operator) | 🛠️ | ⬜ |
| Databases     | MySQL           | Percona XtraDB Cluster | [percona-helm-charts/pxc-operator](https://github.com/percona/percona-helm-charts/tree/main/charts/pxc-operator) | 🛠️ | ⬜ |
| Databases     | MongoDB         | Percona MongoDB        | [percona-helm-charts/psmdb-operator](https://github.com/percona/percona-helm-charts/tree/main/charts/psmdb-operator) | 🛠️ | ⬜ |
| Databases     | CouchDB         | Apache CouchDB         | [apache/couchdb-helm](https://github.com/apache/couchdb-helm/tree/main/couchdb) | 📦 | ⬜ |
| Databases     | Couchbase       | Couchbase              | [couchbase-partners/helm-charts/couchbase-operator](https://github.com/couchbase-partners/helm-charts/tree/master/charts/couchbase-operator) | 🛠️ | ⬜ |
| Databases     | ScyllaDB        | ScyllaDB              | [scylladb/scylla-operator](https://github.com/scylladb/scylla-operator/tree/master/helm) | 🛠️ | ⬜ |
| Databases     | Redis           | Redis                 | [OT-CONTAINER-KIT/redis-operator](https://github.com/OT-CONTAINER-KIT/redis-operator/tree/main/charts/redis-operator) | 🛠️ | ⬜ |
| Data          | Redpanda        | Redpanda Controller    | [redpanda-operator/charts/redpanda](https://github.com/redpanda-data/redpanda-operator/tree/main/charts/redpanda) | ⚙️ | ⬜ |
| Data          | Redpanda        | Redpanda               | [redpanda-operator/operator/chart](https://github.com/redpanda-data/redpanda-operator/tree/main/operator/chart) | 🛠️ | ⬜ |
| Data          | InfluxDB        | InfluxDB              | [influxdata/helm-charts](https://github.com/influxdata/helm-charts) | 📦 | ⬜ |
| Data          | OpenSearch      | OpenSearch            | [opensearch-project/helm-charts](https://github.com/opensearch-project/helm-charts/tree/main/charts) | 📦 | ⬜ |
| Networking    | External DNS    | External DNS           | [kubernetes-sigs/external-dns](https://github.com/kubernetes-sigs/external-dns/tree/master/charts/external-dns) | ⚙️ | ⬜ |
| Networking    | Consul          | Consul                | [hashicorp/consul-k8s](https://github.com/hashicorp/consul-k8s/tree/main/charts/consul) | 📦 | ⬜ |
| Networking    | Kong            | Kong                  | [Kong/charts](https://github.com/Kong/charts/tree/main/charts) | 📦 | ⬜ |
| Identity      | Cert Manager    | Cert Manager           | [cert-manager/cert-manager](https://github.com/cert-manager/cert-manager/tree/master/deploy/charts/cert-manager) | ⚙️ | ⬜ |
| Identity      | Vault           | Vault                 | [hashicorp/vault-helm](https://github.com/hashicorp/vault-helm) | 📦 | ⬜ |
| Applications  | Argo CD         | Argo CD                | [argo-helm/argo-cd](https://github.com/argoproj/argo-helm/tree/main/charts/argo-cd) | ⚙️ | ⬜ |
| Applications  | Argo Workflows  | Argo Workflows         | [argo-helm/argo-workflows](https://github.com/argoproj/argo-helm/tree/main/charts/argo-workflows) | ⚙️ | ⬜ |
| Applications  | Nominatim       | Nominatim              | [robjuz/helm-charts/nominatim](https://github.com/robjuz/helm-charts/tree/master/charts/nominatim) | 📦 | ⬜ |
| Applications  | Jenkins         | Jenkins               | [jenkinsci/helm-charts](https://github.com/jenkinsci/helm-charts/tree/main/charts/jenkins) | 📦 | ⬜ |
| Applications  | SonarQube       | SonarQube             | [SonarSource/helm-chart-sonarqube](https://github.com/SonarSource/helm-chart-sonarqube/tree/master/charts) | 📦 | ⬜ |
| Data          | Solr            | Solr                  | [apache/solr-operator](https://github.com/apache/solr-operator/tree/main/helm) | 🛠️ | ⬜ |

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
