# kf-app-tekton

## Installation

```bash
# Latest version
kubectl apply --filename https://storage.googleapis.com/tekton-releases/pipeline/latest/release.yaml
# Previous version
TEKTON_VERSION=v0.2.0
kubectl apply --filename https://storage.googleapis.com/tekton-releases/pipeline/previous/${TEKTON_VERSION}/release.yaml
```
