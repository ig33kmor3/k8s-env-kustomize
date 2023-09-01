# k8s-env-kustomize
Kubernetes Multi-Environment Kustomize for On-Premise and Cloud Demonstration

[Official Documentation](https://kubectl.docs.kubernetes.io/references/kustomize/kustomization/)

## Kustomize folder structure
- application/
    - base/
    - overlays/
        - development/
        - staging/
        - production/

## Install kustomize and kubectl as required
```bash
brew install kustomize
brew install kubectl
```