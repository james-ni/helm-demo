A demo project for learning Kubernetes and Helm.

## Hello world

This helm chart includes a simple web application, which is exposed to outside using ingress.

```bash
# This will install the app running at http://<YOUR_KUBERNETES_HOST>
helm install hello-world ./hello-world
```

