This project include exercise:
- 2.01

```bash
docker build -t thangnv2212/pong-app . && docker push thangnv2212/pong-app

kubectl apply -f manifests/deployment.yaml
kubectl apply -f manifests/service.yaml
kubectl apply -f manifests/ingress.yaml
```

Deployed to localhost:8081/pingpong