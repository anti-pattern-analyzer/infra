# infrastructure 

```
docker network create logging-wrapper
```

```
kubectl apply -f namespace.yaml
kubectl apply -f pvc.yaml
kubectl apply -f timescaledb.yaml
kubectl apply -f zookeeper.yaml
kubectl apply -f kafka-1.yaml
kubectl apply -f neo4j.yaml
kubectl apply -f kafka-ui.yaml
```

```
kubectl get pods -n logging-wrapper
```