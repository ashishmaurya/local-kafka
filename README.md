# local-kafka
Running kafka on local mahcine(Kubernetes Cluster)

1. Run the Zookeeper
  `k apply -f zookeeper.yaml`
2. Run Kafka 
  `k apply -f kafka.yaml`
3. Run Kafka UI Service 
  `k apply -f kafka-ui.yaml`
  
Now Access the service on `cluster-ip:31006`
