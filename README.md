# local-kafka
Running kafka on local mahcine(Kubernetes Cluster)

1. Run the Zookeeper
  `k applly -f zookeeper.yaml`
2. Run Kafka 
  `k applly -f kafka.yaml`
3. Run Kafka UI Service 
  `k applly -f kafka-ui.yaml`
  
Now Access the service on `cluster-ip:31006`
