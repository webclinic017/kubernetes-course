This project include exercise:
- 1.01
- 1.03
- 1.07

```bash
docker build -t thangnv2212/main-app .
docker push thangnv2212/main-app
kubectl apply -f manifests/deployment.yaml
kubectl logs -f --tail=10 main-dep-6f87f9fdf9-f7wgl

kubectl apply -f manifests/service.yaml
kubectl apply -f manifests/ingress.yaml
```