# Kubernetes Infrastructure Lab

This repository contains hands-on Kubernetes projects, infrastructure scenarios, and deployment experiments created for learning, practice, and portfolio development.

Each project focuses on a different Kubernetes concept or production-style scenario, such as:

* Deployments and Services
* Kustomize bases and overlays
* ConfigMaps and Secrets
* Ingress and internal networking
* Stateful workloads and persistent storage
* Horizontal Pod Autoscaling

The projects in this repository are designed as isolated labs. Each project has its own architecture, Kubernetes manifests, configuration, and documentation.

> The main purpose of this repository is to practice Kubernetes infrastructure design. Application images may use demo or mock containers when application source code is not required.

---

## Projects

### 1. KubeShop Kubernetes Platform

A production-style Kubernetes infrastructure project for a fictional e-commerce platform based on a microservices architecture.

The project includes a Frontend, API Gateway, application services, PostgreSQL, Redis, RabbitMQ, environment overlays, networking, autoscaling, security, and observability concepts.

[View the KubeShop Kubernetes Platform project](https://github.com/emaadbh/kubernetes_infrastructure_lab/tree/main/projects/kubeshop-kubernetes-platform)

---

## Repository Structure

```text
kubernetes_infrastructure_lab/
├── README.md
└── projects/
    ├── kubeshop-kubernetes-platform/
    └── future-kubernetes-projects/
```


## Project Status

This repository is a work in progress. New Kubernetes labs and infrastructure scenarios will be added over time.

---

## Purpose

This repository is intended for:

* Kubernetes learning and experimentation
* DevOps and platform engineering practice
* Infrastructure portfolio development
* Testing production-style Kubernetes patterns
* Documenting architecture and operational decisions

