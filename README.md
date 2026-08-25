<img src="./assets/banner.svg" alt="Rameshwar Dudhe — DevOps & Platform Engineer" width="100%">

<p align="center">
  <a href="https://github.com/rameshwar-dudhe?tab=repositories"><img alt="Projects" src="https://img.shields.io/badge/Projects-6-326CE5?style=for-the-badge&logo=github&logoColor=white"></a>
  <img alt="Experience" src="https://img.shields.io/badge/DevOps-3.7%20years-2dd4bf?style=for-the-badge">
  <img alt="Focus" src="https://img.shields.io/badge/Focus-Platform%20%26%20SRE-8b5cf6?style=for-the-badge">
  <img alt="Open to work" src="https://img.shields.io/badge/Open%20to-DevOps%20%7C%20Platform%20%7C%20SRE-22c55e?style=for-the-badge">
</p>

---

## Hi, I'm Rameshwar

DevOps Engineer with **3.7 years** building and running Kubernetes platforms — cluster
provisioning, GitOps delivery, CI/CD, and observability. Across managed control planes
(EKS, GKE), enterprise platforms (OpenShift, vSphere) and bare metal, driven end to end
by Helm, Ansible and Terraform rather than clicked together in a console.

What I care about is the part most tutorials skip: **what happens when the deploy
reports success and the cluster is still broken.** My repos ship the runbook and the
root-cause writeup alongside the code, because the second one is what you actually
need at 2am.

```yaml
role:      DevOps / Platform Engineer
focus:     Kubernetes platform engineering, IaC, GitOps, observability, AI on K8s
approach:  version-pinned · idempotent · reproducible · documented
currently: deepening SRE practice — reliability, incident response, platform UX
open_to:   DevOps · Platform Engineering · SRE
```

---

## Toolbox

**Container platform & orchestration**

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![OpenShift](https://img.shields.io/badge/OpenShift-EE0000?style=flat-square&logo=redhatopenshift&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)
![Kustomize](https://img.shields.io/badge/Kustomize-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Istio](https://img.shields.io/badge/Istio-466BB0?style=flat-square&logo=istio&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![containerd](https://img.shields.io/badge/containerd-575757?style=flat-square&logo=containerd&logoColor=white)

**Cloud & virtualization**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Amazon EKS](https://img.shields.io/badge/Amazon%20EKS-FF9900?style=flat-square&logo=amazoneks&logoColor=white)
![Google GKE](https://img.shields.io/badge/Google%20GKE-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Red Hat](https://img.shields.io/badge/Red%20Hat-EE0000?style=flat-square&logo=redhat&logoColor=white)
![VMware vSphere](https://img.shields.io/badge/VMware%20vSphere-607078?style=flat-square&logo=vmware&logoColor=white)

**Infrastructure as code**

![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)
![Kubespray](https://img.shields.io/badge/Kubespray-0F1689?style=flat-square)

**CI/CD & GitOps**

![Argo CD](https://img.shields.io/badge/Argo%20CD-EF7B4D?style=flat-square&logo=argo&logoColor=white)
![Jenkins X](https://img.shields.io/badge/Jenkins%20X-D24939?style=flat-square&logo=jenkins&logoColor=white)
![CircleCI](https://img.shields.io/badge/CircleCI-343434?style=flat-square&logo=circleci&logoColor=white)
![Bazel](https://img.shields.io/badge/Bazel-43A047?style=flat-square&logo=bazel&logoColor=white)

**Observability & APM**

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Loki](https://img.shields.io/badge/Loki-F5A800?style=flat-square&logo=grafana&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=flat-square&logo=opentelemetry&logoColor=white)
![Datadog](https://img.shields.io/badge/Datadog-632CA6?style=flat-square&logo=datadog&logoColor=white)
![Dynatrace](https://img.shields.io/badge/Dynatrace-1496FF?style=flat-square&logo=dynatrace&logoColor=white)
![New Relic](https://img.shields.io/badge/New%20Relic-1CE783?style=flat-square&logo=newrelic&logoColor=black)

**AI engineering**

![Generative AI](https://img.shields.io/badge/Generative%20AI-412991?style=flat-square&logo=openai&logoColor=white)
![Agentic AI](https://img.shields.io/badge/Agentic%20AI-8B5CF6?style=flat-square&logo=probot&logoColor=white)

**Systems & data**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

---

## Featured work

### [kube-flow](https://github.com/rameshwar-dudhe/kube-flow)
Hybrid **Helm + Kustomize** deployment of Kubeflow 26.03.1 on bare-metal Kubernetes —
KServe, Kubeflow Trainer, Spark Operator, Istio and cert-manager, version-pinned and
idempotent end to end. The kind of install that usually turns into a week of
yak-shaving, reduced to a repeatable run.

### [kubespray-2node-cluster](https://github.com/rameshwar-dudhe/kubespray-2node-cluster)
Kubernetes cluster provisioned with **Kubespray + Ansible**, Make-driven and
reproducible from a single config file. Ships with a full runbook **and a root-cause
analysis of a CoreDNS forwarding loop** that left DNS dead while Ansible cheerfully
reported `failed=0` — the diagnosis, the fix, and why it belongs in the inventory
rather than on the node.

### [terraform-iac](https://github.com/rameshwar-dudhe/terraform-iac)
Standalone **Terraform** configurations for core AWS services — VPC, EC2, ALB, RDS,
ECR, Lambda, IAM, Secrets Manager, EventBridge and Step Functions. Composable building
blocks rather than one monolithic stack.

### [kubedoom-k8s](https://github.com/rameshwar-dudhe/kubedoom-k8s)
**Helm chart** deploying KubeDoom with hardened, tightly scoped RBAC. A genuinely fun
project that doubles as a practical exercise in least-privilege service accounts.

### [mongo-replication-made-easy](https://github.com/rameshwar-dudhe/mongo-replication-made-easy-)
Step-by-step guide and command logs for a two-node **MongoDB replica set** on Ubuntu —
written so someone else can follow it without guessing.

---

## In the pipeline

Working toward public release: Argo CD self-healing GitOps, Jenkins X on
Ansible-provisioned HA Kubernetes, Velero backup and restore, a full
Prometheus/Grafana/Loki monitoring stack, OpenTelemetry instrumentation, and
Bazel-built CI pipelines.

---

## Activity

<p align="center">
  <img height="165" alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=rameshwar-dudhe&show_icons=true&hide_border=true&theme=github_dark&bg_color=0d1117&title_color=326CE5&icon_color=2dd4bf&text_color=8b98a8">
  <img height="165" alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=rameshwar-dudhe&layout=compact&hide_border=true&theme=github_dark&bg_color=0d1117&title_color=326CE5&text_color=8b98a8">
</p>

---

## Reach me

<p align="center">
  <a href="mailto:rndudhe1808@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"></a>
  <a href="https://github.com/rameshwar-dudhe"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"></a>
</p>

<p align="center"><sub>Open to DevOps, Platform Engineering and SRE roles.</sub></p>
