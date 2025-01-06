# Observability_Project


This repository contains the OpenTelemetry Astronomy Shop, a microservice-based distributed system intended to illustrate the implementation of OpenTelemetry in a near real-world environment


```
kubectl apply --namespace otel-demo -f https://raw.githubusercontent.com/open-telemetry/opentelemetry-demo/main/kubernetes/opentelemetry-demo.yaml
```

```
kubectl port-forward -n otel-demo svc/opentelemetry-demo-frontendproxy 8080:8080 --address 0.0.0.0
```
