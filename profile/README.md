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

## ⚡ Alternative Operators

For database workloads it is often more convenient to use operators, which provide advanced lifecycle management.  
Below are recommended Percona Operators:

| Chart        | Recommended Operator                  | Link                                                                 |
|--------------|---------------------------------------|----------------------------------------------------------------------|
| 🐘 PostgreSQL | Percona PostgreSQL Operator           | [percona-helm-charts/pg-operator](https://github.com/percona/percona-helm-charts/tree/main/charts/pg-operator) |
| 🐬 MySQL      | Percona XtraDB Cluster Operator (PXC) | [percona-helm-charts/pxc-operator](https://github.com/percona/percona-helm-charts/tree/main/charts/pxc-operator) |
| 🍃 MongoDB    | Percona MongoDB Operator              | [percona-helm-charts/psmdb-operator](https://github.com/percona/percona-helm-charts/tree/main/charts/psmdb-operator) |

Operators include:  
✅ High Availability • ✅ Automated Backups • ✅ Monitoring Integration • ✅ Full Lifecycle Management  

---

## 🎯 Goal

The purpose of this repository is to keep free and accessible charts available for **testing, prototyping, and education**,  
and at the same time highlight alternatives such as **operators** that may be a better fit for production environments.
