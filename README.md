Kafka Demo
---

Provision a Kafka cluster without Zookeeper ensemble and production ready related stack on Kubernetes.

## Kafka (Kraft mode)

 - version: 3.6.0
 - operator: strimzi-kafka-operator(0.38.0)

## Kafka UI

![kafka-ui](./kafka-ui.png)

## Prometheus & Grafana
 - monitoring: ![prometheus-metrics](./prometheus-metrics.png)
 - alerting: ![alerting](./alerting.png)
 - dashboard: ![kafka-cluster](./kafka-cluster.png)

## K6 (Testing)
![k6](./k6-testing.png)

## Vector (Consumer)
 - version: 0.34.1

## KEDA (Auto-scaling)
 - version: 2.12.0


