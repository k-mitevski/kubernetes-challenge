### This is a Kubernetes challenge from learnk8s that runs inside Minikube.
### If all works well, doing a curl on minikube should return you with my name.

### To start it run the following commands from inside the folder:
1. `minikube start`
2. `eval $(minikube docker-env)`
3. `docker build -t lk8s:1.0 .`
4. `kubectl apply -f manifests`
5. `curl $(minikube ip)`
