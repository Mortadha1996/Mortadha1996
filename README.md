# Infrastructure & Platform Engineer

I run production infrastructure and build the automation that keeps it healthy.

Currently at Sagemcom: a 148-server estate across 12+ VMware ESXi hosts, 
a zero-downtime Docker-to-Kubernetes migration, 100+ systems under Ansible, 
and an in-house AIOps platform that predicts failures before they cause incidents.

## Projects

🔍 **aiops-anomaly-detection** — ML pipeline on Prometheus and Loki telemetry.
Unsupervised bootstrap labelling, seven-model competition with recall-weighted 
scoring, ONNX export, MLflow tracking. 0.984 F1 in production.

🚀 **llm-inference-platform** — Self-hosted LLM serving on Kubernetes with GPU.
vLLM, ArgoCD GitOps with self-heal, DCGM + Prometheus + Grafana, SLOs with 
multi-window burn rate alerting, Checkov policy-as-code in CI.

☁️ **aws-ha-architecture** — Multi-AZ web architecture in Terraform.
ALB, Auto Scaling Group, RDS Multi-AZ. Tested by terminating instances under 
load — 1 failed request of ~40. RDS failover: 15 seconds, DNS unchanged.

📊 **k8s-monitoring-chart** — Helm chart: Prometheus, Grafana, Alertmanager,
node-exporter, kube-state-metrics. Predictive disk alerting with predict_linear,
automatic pod discovery via annotations. One command install.

## Stack

Kubernetes · Ansible · Terraform · AWS · Helm · ArgoCD · Prometheus · Grafana · Python

## Certifications

RHCE · RHCSA · Red Hat Ansible (×2) · EX188 · AWS Solutions Architect · CCNA · 
eCPPT · CRTA · ISO 27001

## Writing

📄 [Manage Windows Server machines with Ansible](https://medium.com/) — Medium

## Links

[LinkedIn](https://www.linkedin.com/in/mortadha-riahi/) · 
[GitHub](https://github.com/Mortadha1996)
