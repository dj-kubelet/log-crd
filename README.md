# Kubernetes Log CRD

Does `kubectl get logs` disappoint you?
Add a cheerful message!

## Install
```bash
kubectl apply -f ./log-crd.yaml
kubectl apply -f ./log1.yaml
```

## Usage
```bash
$ kubectl get logs
NAME   MESSAGE
a
    Multi
          line
               yaml
```
