# Build and push docker image to dockerhub
```
docker build -t freemanpolys/mission-dev .
docker push freemanpolys/mission-dev

```

# Deploy the express app in eks with loadbalancer service

```
cd deploy
kubectl apply -f .
```
