# docker-kubectl
Alpine based thin docker image for just doing `kubectl` command.

```
docker build -t jaychap/kubectl-123 .
docker run -it jaychap/kubectl-123
docker push jaychap/kubectl-123
kubectl run  -it --rm --restart='Never' --image=jaychap/kubectl:latest kubectl-pod

```