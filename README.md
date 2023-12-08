# gpu-stress-app

Remove everything


### Kubernetes Usage
Default run-time:
```bash
kubectl apply -f deploy.yaml
```
> *Note*: delete the running `kubernetes` pod via: `kubectl delete pod gpu-test`

This Stress App is capable of running on MIG enabled GPUs as well as MIG disabled GPUs

Docker image to be used
```bash
docker pull alloydsavio/gpu-stress-test
```
