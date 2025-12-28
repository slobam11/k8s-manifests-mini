# Kubernetes Mini Manifests – Ops Focus

This repository contains a minimal but production-oriented Kubernetes setup
focused on **operations basics** such as health checks, resource management
and basic troubleshooting.

The goal is not to build a complex application, but to demonstrate how a
Kubernetes workload should be deployed and operated in a real environment.

---

## 🎯 Goal

- Deploy a simple application to Kubernetes
- Use **readiness and liveness probes**
- Apply **resource requests and limits**
- Practice **basic Kubernetes troubleshooting**
- Document ops-level thinking, not just YAML syntax

---

## 🧱 Components

- Kubernetes Deployment
- Kubernetes Service
- Readiness & Liveness probes
- Resource requests & limits

---

## 📋 Prerequisites

- Kubernetes cluster (minikube or kind)
- kubectl
- Docker (only if using local images)

---

## 🚀 Deployment

```bash
kubectl apply -f .


## Verify resources :
kubectl get pods
kubectl get svc
