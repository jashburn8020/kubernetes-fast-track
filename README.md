# Kubernetes Fast-Track with MicroK8s

## Kubernetes 101

- Pod
  - smallest object in Kubernetes
  - one or more containers
  - best practice to have 1 container per pod
    - if there is a problem with 1 container, K8s can mark the entire pod as unhealthy and stop it from starting up
  - a pod is wrapped by a **replica set**
- Replica set
  - controls the number of pods available
  - wrapped by a **deployment**
- Deployment
  - allows us to rollback and roll-forward with updates

## Sources

- Warp 9 Training. "Ultimate Kubernetes Fast-Track Beginner to Advanced." _Udemy_, Udemy, May 2020, [www.udemy.com/course/kubernetes-fast-track](https://www.udemy.com/course/kubernetes-fast-track/).
