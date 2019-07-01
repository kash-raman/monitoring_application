# monitoring_application
Setup microservices with monitoring and stats using Grafana and Prometheus.
Add below properties in Docker application 

{
  "metrics-addr" : "127.0.0.1:9786",
  "experimental" : true,
  "debug" : true
}

Command: 

docker-compose -f docker-compose.yml -f docker-compose-dev-mac.yml up -d 

