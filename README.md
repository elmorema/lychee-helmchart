# lychee-helmchart

## prerequisites

* have `helm` installed on your computer
* have `cert-manager` installed in your cluster

## installation

```bash
kubectl create namespace lychee
helm repo add lychee https://breuerfelix.github.io/lychee-helmchart
helm repo update
helm install lychee lychee/lychee -n lychee
```
