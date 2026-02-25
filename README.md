# kubernetes-microservices-platform
## Overview
This repository contains production-ready Kubernetes manifests and Helm charts designed for scalable microservices deployments.

## Features
- Rolling update deployment strategy
- Resource requests and limits enforcement
- Readiness probe configuration
- Horizontal Pod Autoscaler (HPA)
- Ingress-based external routing
- Helm chart templating for environment reuse

## Architecture
- Designed for AWS EKS / Azure AKS
- Supports containerized microservices
- Production-grade scaling configuration

## Deployment

Using kubectl:
kubectl apply -f base-manifests/

Using Helm:
helm install enterprise-app ./helm-chart

## Best Practices Implemented
- Zero-downtime deployments
- Autoscaling configuration
- Resource governance
- Health checks and monitoring readiness
