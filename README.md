example create cluster kind
---

1. Cluster 1 control node. 3 worker

```bash
kind create cluster --config kind-c1-w3.yaml
```
Delete cluster
```bash
kind delete cluster --name kind-c1-w3
```

---
2. Cluster 1 control node, 5 worker (3 worker + 2 worker ingress)

```bash
kind create cluster --config kind-c1-w3-wi2.yaml
```
Delete cluster
```bash
kind delete cluster --name kind-c1-w3-wi2
```
---

