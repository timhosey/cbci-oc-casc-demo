# CloudBees CI CasC for OC Demo

## Instructions
Use `oc-casc-bundle.yaml` as a ConfigMap:

```
kubectl apply -f oc-casc-bundle.yaml
```

Use `gke_cjoc_values.yaml` for Helm install of CBCI:

```
helm install cloudbees-core cloudbees/cloudbees-core -f gke_cjoc_values.yaml --namespace cloudbees-core
```
