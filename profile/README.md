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

| Chart          | Alternative                             | Link                                                                 | Type        | Adopted by Opsolving |
|----------------|-----------------------------------------|----------------------------------------------------------------------|-------------|-----------------------|
| 🐘 PostgreSQL   | Percona PostgreSQL Operator             | [percona-helm-charts/pg-operator](https://github.com/percona/percona-helm-charts/tree/main/charts/pg-operator) | ✅ Operator | 🔄 If abandoned |
| 🐬 MySQL        | Percona XtraDB Cluster Operator (PXC)   | [percona-helm-charts/pxc-operator](https://github.com/percona/percona-helm-charts/tree/main/charts/pxc-operator) | ✅ Operator | 🔄 If abandoned |
| 🍃 MongoDB      | Percona MongoDB Operator                | [percona-helm-charts/psmdb-operator](https://github.com/percona/percona-helm-charts/tree/main/charts/psmdb-operator) | ✅ Operator | 🔄 If abandoned |
| 🔐 Cert Manager | Official Cert Manager Chart             | [cert-manager/cert-manager](https://github.com/cert-manager/cert-manager/tree/master/deploy/charts/cert-manager) | ⚙️ Controller | 🔄 If abandoned |
| 🌍 External DNS | Official External DNS Chart             | [kubernetes-sigs/external-dns](https://github.com/kubernetes-sigs/external-dns/tree/master/charts/external-dns) | ⚙️ Controller | 🔄 If abandoned |
| 🦊 Redpanda     | Redpanda Controller                     | [redpanda-operator/charts/redpanda](https://github.com/redpanda-data/redpanda-operator/tree/main/charts/redpanda) | ⚙️ Controller | 🔄 If abandoned |
| 🦊 Redpanda     | Redpanda Operator                       | [redpanda-operator/operator/chart](https://github.com/redpanda-data/redpanda-operator/tree/main/operator/chart) | ✅ Operator | 🔄 If abandoned |
| 🗺️ Nominatim    | Community Nominatim Helm Chart          | [robjuz/helm-charts/nominatim](https://github.com/robjuz/helm-charts/tree/master/charts/nominatim) | 📦 Helm Chart | 🔄 If abandoned |

---

## 🎯 Goal

This repository maintains a set of free and accessible Helm charts for commonly used services,  
while also providing references to operator-based solutions for cases where extended functionality is useful.
