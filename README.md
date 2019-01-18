# kafka-grafana
After you've cloned the repository, just run

    docker-compose up

This will run a Kafka broker, Prometheus and Grafana in the same host. You must configure grafana to import Prometheus data source [which is described at the end of the main article](https://medium.com/@mousavi310/monitor-apache-kafka-using-grafana-and-prometheus-873c7a0005e2).