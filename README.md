# ☸️ Kubernetes Kind Hands-On Project

This repository documents my hands-on learning and practice with Kubernetes using Kind (Kubernetes IN Docker).

During this project, I created a multi-node Kubernetes cluster, configured kubectl, created Namespaces and Pods, deployed applications using Kubernetes Deployments, practiced replica scaling, and worked through real Kubernetes troubleshooting scenarios.

---

## 🚀 Project Overview

The main objective of this project was to understand Kubernetes fundamentals through practical implementation rather than only theoretical learning.

### Topics Covered

- Kubernetes Architecture
- Kubernetes Control Plane
- Worker Nodes
- Docker
- Kind
- kubectl
- Kubernetes Cluster Creation
- Namespaces
- Pods
- Deployments
- ReplicaSets
- YAML Manifests
- Container Images
- Container Ports
- Replica Scaling
- Kubernetes Troubleshooting
- ImagePullBackOff
- Kubernetes Resource Management

---

## 🏗️ Kubernetes Architecture

The Kubernetes cluster created during this project consisted of:

- 1 Control Plane
- 3 Worker Nodes

```text
                    Kubernetes Cluster
                           |
                    Control Plane
                           |
          +----------------+----------------+
          |                |                |
     Worker Node 1    Worker Node 2    Worker Node 3
          |                |                |
         Pods             Pods             Pods
