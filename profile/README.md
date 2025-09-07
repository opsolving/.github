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

| Chart          | Alternative                             | Link                                                                 | Type | ♻️ Adopted |
|----------------|-----------------------------------------|----------------------------------------------------------------------|------|------------|
| 🐘 PostgreSQL   | Percona PostgreSQL Operator             | [percona-helm-charts/pg-operator](https://github.com/percona/percona-helm-charts/tree/main/charts/pg-operator) | 🛠️ | ⬜ |
| 🐬 MySQL        | Percona XtraDB Cluster Operator (PXC)   | [percona-helm-charts/pxc-operator](https://github.com/percona/percona-helm-charts/tree/main/charts/pxc-operator) | 🛠️ | ⬜ |
| 🍃 MongoDB      | Percona MongoDB Operator                | [percona-helm-charts/psmdb-operator](https://github.com/percona/percona-helm-charts/tree/main/charts/psmdb-operator) | 🛠️ | ⬜ |
| 🔐 Cert Manager | Official Cert Manager Chart             | [cert-manager/cert-manager](https://github.com/cert-manager/cert-manager/tree/master/deploy/charts/cert-manager) | ⚙️ | ⬜ |
| 🌍 External DNS | Official External DNS Chart             | [kubernetes-sigs/external-dns](https://github.com/kubernetes-sigs/external-dns/tree/master/charts/external-dns) | ⚙️ | ⬜ |
| 🦊 Redpanda     | Redpanda Controller                     | [redpanda-operator/charts/redpanda](https://github.com/redpanda-data/redpanda-operator/tree/main/charts/redpanda) | ⚙️ | ⬜ |
| 🦊 Redpanda     | Redpanda Operator                       | [redpanda-operator/operator/chart](https://github.com/redpanda-data/redpanda-operator/tree/main/operator/chart) | 🛠️ | ⬜ |
| 🗺️ Nominatim    | Community Nominatim Helm Chart          | [robjuz/helm-charts/nominatim](https://github.com/robjuz/helm-charts/tree/master/charts/nominatim) | 📦 | ⬜ |

---

### 🔑 Legend

- 🛠️ Operator  
- ⚙️ Controller  
- 📦 Helm Chart  
- ⬜ Planned adoption (if abandoned by community)  
- ☑️ Adopted by Opsolving (active maintenance)

---

## 🎯 Goal

This repository keeps a set of free and accessible Helm charts for commonly used services.  
If any chart is abandoned by the community, **Opsolving adopts and maintains it** to ensure continuity, stability, and availability.
