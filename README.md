# IoT App - Kubernetes Manifests

This repository contains Kubernetes manifests for the IoT application.
It's used by ArgoCD for continuous deployment (GitOps).

## Files

- `deployment.yaml` - Application deployment
- `service.yaml` - Kubernetes service
- `ingress.yaml` - Ingress configuration

## GitOps Workflow

Push changes to this repo → ArgoCD automatically deploys changes to cluster.
