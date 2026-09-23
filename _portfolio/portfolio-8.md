---
title: "Scalable Event Processing with Kubernetes"
excerpt: "
Built an Azure event-processing pipeline with AKS, Event Hubs, and PostgreSQL, provisioned with Terraform and Helm and configured for autoscaling on a B2ms AKS cluster. Supported approximately 10–15k events per minute through Event Hubs backpressure and idempotent batch writes, preventing database overload during burst traffic. Added Prometheus and Grafana monitoring for p95 latency, worker lag, and throughput, and validated the system with Locust production-style load testing.
<br/>Concepts: Event-Driven Architecture, Backpressure, Autoscaling, Observability
<br/>Skills: Azure, AKS, Event Hubs, PostgreSQL, Terraform, Helm, Prometheus, Grafana, Locust"
collection: Projects
---
[Code](https://github.com/SuhaasKiran/scalable-events-processing)
