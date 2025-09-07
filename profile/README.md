# 📦 Opsolving Helm Charts

A collection of **open-source Helm charts** for widely used services and components.  
Created as community-driven alternatives after Bitnami charts moved to a commercial model.

---

## 📚 Available Charts

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?logo=postgresql&logoColor=white&style=flat-square)  
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white&style=flat-square)  
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white&style=flat-square)  
![Keycloak](https://img.shields.io/badge/Keycloak-2C4C7E?logo=keycloak&logoColor=white&style=flat-square)  
![KeyDB](https://img.shields.io/badge/KeyDB-D82C20?logo=redis&logoColor=white&style=flat-square)  
![Tomcat](https://img.shields.io/badge/Tomcat-F8DC75?logo=apachetomcat&logoColor=black&style=flat-square)  
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?logo=rabbitmq&logoColor=white&style=flat-square)  
![WildFly](https://img.shields.io/badge/WildFly-007ACC?logo=wildfly&logoColor=white&style=flat-square)  
![OpenLDAP](https://img.shields.io/badge/OpenLDAP-1D76DB?logo=openldap&logoColor=white&style=flat-square)  
![phpMyAdmin](https://img.shields.io/badge/phpMyAdmin-6C78AF?logo=php&logoColor=white&style=flat-square)  
![Kafka](https://img.shields.io/badge/Kafka-231F20?logo=apachekafka&logoColor=white&style=flat-square)  
![Zookeeper](https://img.shields.io/badge/Zookeeper-FFCA28?logo=apache&logoColor=black&style=flat-square)  
![Logstash](https://img.shields.io/badge/Logstash-005571?logo=elastic&logoColor=white&style=flat-square)  
![NGINX](https://img.shields.io/badge/NGINX-009639?logo=nginx&logoColor=white&style=flat-square)  
![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white&style=flat-square)  
![Common Base Chart](https://img.shields.io/badge/Common--Base--Chart-555555?style=flat-square)

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
