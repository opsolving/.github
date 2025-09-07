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

Some charts have well-maintained operator- or controller-based solutions that extend functionality with automation and advanced management features:  

| Category        | Chart             | Alternative                             | Link                                                                 | Type | Adopted |
|-----------------|-------------------|-----------------------------------------|----------------------------------------------------------------------|------|------------|
| 🗄️ Databases    | 🐘 PostgreSQL      | Percona PostgreSQL Operator             | [percona-helm-charts/pg-operator](https://github.com/percona/percona-helm-charts/tree/main/charts/pg-operator) | 🛠️ | ⬜ |
| 🗄️ Databases    | 🐬 MySQL           | Percona XtraDB Cluster Operator (PXC)   | [percona-helm-charts/pxc-operator](https://github.com/percona/percona-helm-charts/tree/main/charts/pxc-operator) | 🛠️ | ⬜ |
| 🗄️ Databases    | 🍃 MongoDB         | Percona MongoDB Operator                | [percona-helm-charts/psmdb-operator](https://github.com/percona/percona-helm-charts/tree/main/charts/psmdb-operator) | 🛠️ | ⬜ |
| 🗄️ Databases    | 🍪 CouchDB         | Official Apache CouchDB Chart           | [apache/couchdb-helm](https://github.com/apache/couchdb-helm/tree/main/couchdb) | 📦 | ⬜ |
| 🗄️ Databases    | 🛋️ Couchbase      | Couchbase Operator                      | [couchbase-partners/helm-charts/couchbase-operator](https://github.com/couchbase-partners/helm-charts/tree/master/charts/couchbase-operator) | 🛠️ | ⬜ |
| 📡 Data         | 🦊 Redpanda      | Redpanda Controller                     | [redpanda-operator/charts/redpanda](https://github.com/redpanda-data/redpanda-operator/tree/main/charts/redpanda) | ⚙️ | ⬜ |
| 📡 Data         | 🦊 Redpanda      | Redpanda Operator                       | [redpanda-operator/operator/chart](https://github.com/redpanda-data/redpanda-operator/tree/main/operator/chart) | 🛠️ | ⬜ |
| 🌍 Networking   | 🌍 External DNS    | Official External DNS Chart             | [kubernetes-sigs/external-dns](https://github.com/kubernetes-sigs/external-dns/tree/master/charts/external-dns) | ⚙️ | ⬜ |
| 🔐 Identity     | 🔐 Cert Manager    | Official Cert Manager Chart             | [cert-manager/cert-manager](https://github.com/cert-manager/cert-manager/tree/master/deploy/charts/cert-manager) | ⚙️ | ⬜ |
| 📦 Applications | 🎯 Argo CD         | Official Argo CD Chart                  | [argo-helm/argo-cd](https://github.com/argoproj/argo-helm/tree/main/charts/argo-cd) | ⚙️ | ⬜ |
| 📦 Applications | 🎯 Argo Workflows  | Official Argo Workflows Chart           | [argo-helm/argo-workflows](https://github.com/argoproj/argo-helm/tree/main/charts/argo-workflows) | ⚙️ | ⬜ |
| 📦 Applications | 🗺️ Nominatim      | Community Nominatim Helm Chart          | [robjuz/helm-charts/nominatim](https://github.com/robjuz/helm-charts/tree/master/charts/nominatim) | 📦 | ⬜ |

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
