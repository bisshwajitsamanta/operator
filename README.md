# operator
First Kubernetes Operator

# Steps to configure 
    * go install sigs.k8s.io/kind@v0.15.0
    * kind create cluster --name guru-operator-dev
    * kind get clusters
    * kubectl cluster-info --context kind-guru-operator-dev
    * kind delete cluster --name guru-operator-dev
