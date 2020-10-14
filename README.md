# poc-node-app

### TO-DO
- Setup minikube cluster -- done
    ```
        minikube start --memory=2048 --cpus=2 --bootstrapper=kubeadm --extra-config=apiserver.authorization-mode=RBAC --kubernetes-version="1.16.13"
    ```
- Jenkinsfile
    - parameter tag
    - to create docker image and push with that tag
    - update deployment.yaml with image tag
    - apply k8s minikube
- Setup kustomization base and overlay
