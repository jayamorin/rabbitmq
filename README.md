# Rabbit MQ

## Installation

```bash
kubectl apply -k overlays/docker-desktop

kubectl get secret rabbitmq-hello-world-default-user -o jsonpath="{.data.username}" | base64 --decode
kubectl get secret rabbitmq-hello-world-default-user -o jsonpath="{.data.password}" | base64 --decode
```

## Reference

* [RabbitMQ](https://www.rabbitmq.com/)
* [Kustomize.io](https://kustomize.io/)
