# Observability_Project


This repository contains the OpenTelemetry Astronomy Shop, a microservice-based distributed system intended to illustrate the implementation of OpenTelemetry in a near real-world environment


```
kubectl apply --namespace otel-demo -f https://raw.githubusercontent.com/open-telemetry/opentelemetry-demo/main/kubernetes/opentelemetry-demo.yaml
```

```
kubectl port-forward -n otel-demo svc/opentelemetry-demo-frontendproxy 8080:8080 --address 0.0.0.0
```

```
k get pods -A
```
![image](https://github.com/user-attachments/assets/f3c279e2-5a76-4ea8-8d23-f0609e7f9da6)


```
k get svc -A
```
![image](https://github.com/user-attachments/assets/badaee7a-652c-4460-98ca-c6f2d84d41e7)


Jaegar

![image](https://github.com/user-attachments/assets/f9526876-f982-4c30-8d9a-951a70808618)
