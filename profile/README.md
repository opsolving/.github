# 📦 Opsolving Helm Charts

This repository provides a collection of **open-source Helm charts** for widely used services and components.  
The charts are designed as community-driven alternatives to commercial offerings after Bitnami charts became paid.

---

## 📚 Available Charts

- 🐘 **PostgreSQL**
- 🐬 **MySQL**
- 🍃 **MongoDB**
- 🦄 **Keycloak**
- 🔑 **KeyDB**
- ☕ **Tomcat**
- 🐇 **RabbitMQ**
- 🧩 **WildFly**
- 🗄️ **OpenLDAP**
- 🗂️ **phpMyAdmin**
- 📊 **Kafka**
- 📡 **Zookeeper**
- 📥 **Logstash**
- 🌐 **NGINX**
- 🔴 **Redis** / **Redis Cluster**
- 🔧 **Common base chart**

---

## ⚠️ Recommended Usage

For production-grade **databases**, Helm charts from this repository are **not recommended**.  
Instead, use official **Percona Operators**:

| Chart        | Recommended Operator                  | Link                                                                 |
|--------------|---------------------------------------|----------------------------------------------------------------------|
| 🐘 PostgreSQL | Percona PostgreSQL Operator           | [percona-helm-charts/pg-operator](https://github.com/percona/percona-helm-charts/tree/main/charts/pg-operator) |
| 🐬 MySQL      | Percona XtraDB Cluster Operator (PXC) | [percona-helm-charts/pxc-operator](https://github.com/percona/percona-helm-charts/tree/main/charts/pxc-operator) |
| 🍃 MongoDB    | Percona MongoDB Operator              | [percona-helm-charts/psmdb-operator](https://github.com/percona/percona-helm-charts/tree/main/charts/psmdb-operator) |

Operators provide:  
✅ High Availability • ✅ Automated Backups • ✅ Monitoring Integration • ✅ Full Lifecycle Management
