# 📦 Opsolving Helm Charts

A collection of **open-source Helm charts** for widely used services and components.  
Created as community-driven alternatives after Bitnami charts moved to a commercial model.

---

## 📚 Available Charts

<table>
<tr>
<td valign="top">

### 🗄️ Databases
🐘 PostgreSQL • 🐬 MySQL • 🍃 MongoDB • 🔴 Redis • 🔴 Redis Cluster • 🗂️ phpMyAdmin

</td>
<td valign="top">

### 📡 Data & Streaming
📊 Kafka • 📡 Zookeeper • 📥 Logstash • 🐇 RabbitMQ • 🦊 Redpanda

</td>
<td valign="top">

### 🔐 Identity & Web
🦄 Keycloak • 🔑 KeyDB • ☕ Tomcat • 🧩 WildFly • 🗄️ OpenLDAP • 📜 EJBCA

</td>
</tr>
</table>

---

## ⚡ Alternatives

Some charts have well-maintained operator- or controller-based solutions that extend functionality with automation and advanced management features:  

| Chart          | Alternative                             | Link                                                                 | Type        |
|----------------|-----------------------------------------|----------------------------------------------------------------------|-------------|
| 🐘 PostgreSQL   | Percona PostgreSQL Operator             | [percona-helm-charts/pg-operator](https://github.com/percona/percona-helm-charts/tree/main/charts/pg-operator) | ✅ Operator |
| 🐬 MySQL        | Percona XtraDB Cluster Operator (PXC)   | [percona-helm-charts/pxc-operator](https://github.com/percona/percona-helm-charts/tree/main/charts/pxc-operator) | ✅ Operator |
| 🍃 MongoDB      | Percona MongoDB Operator                | [percona-helm-charts/psmdb-operator](https://github.com/percona/percona-helm-charts/tree/main/charts/psmdb-operator) | ✅ Operator |
| 🔐 Cert Manager | Official Cert Manager Chart             | [cert-manager/cert-manager](https://github.com/cert-manager/cert-manager/tree/master/deploy/charts/cert-manager) | ⚙️ Controller |
| 🌍 External DNS | Official External DNS Chart             | [kubernetes-sigs/external-dns](https://github.com/kubernetes-sigs/external-dns/tree/master/charts/external-dns) | ⚙️ Controller |
| 🦊 Redpanda     | Redpanda Controller                     | [redpanda-operator/charts/redpanda](https://github.com/redpanda-data/redpanda-operator/tree/main/charts/redpanda) | ⚙️ Controller |
| 🦊 Redpanda     | Redpanda Operator                       | [redpanda-operator/operator/chart](https://github.com/redpanda-data/redpanda-operator/tree/main/operator/chart) | ✅ Operator |
| 🗺️ Nominatim    | Community Nominatim Helm Chart          | [robjuz/helm-charts/nominatim](https://github.com/robjuz/helm-charts/tree/master/charts/nominatim) | 📦 Helm Chart |

Operators offer:  
✅ High Availability • ✅ Automated Backups • ✅ Monitoring Integration • ✅ Full Lifecycle Management  

---

## 🎯 Goal

This repository maintains a set of free and accessible Helm charts for commonly used services,  
while also providing references to operator-based solutions for cases where extended functionality is useful.
