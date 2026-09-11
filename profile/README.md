# Melvin at Simplon.co

DevSecOps training programme at Simplon.co. This organization gathers every
project built along the way: two capstone projects and twenty-seven hands-on
labs covering Azure, Kubernetes, Terraform, containers and CI/CD.

Repositories are prefixed by theme, and every repository carries topics, so
you can also browse by
[terraform](https://github.com/orgs/Melvin-Simplon/repositories?q=topic%3Aterraform),
[kubernetes](https://github.com/orgs/Melvin-Simplon/repositories?q=topic%3Akubernetes)
or [azure](https://github.com/orgs/Melvin-Simplon/repositories?q=topic%3Aazure).

## Capstone projects

| Project | What it does |
| --- | --- |
| [capstone-aks-gitops-platform](https://github.com/Melvin-Simplon/capstone-aks-gitops-platform) | End-to-end Azure platform with Terraform and GitLab CI. Entra ID identity access, AKS with remote Velero backups, zero credentials in Git or Kubernetes. |
| [capstone-quiz-frontend](https://github.com/Melvin-Simplon/capstone-quiz-frontend) | Angular 22 app for revising Azure certifications, by module or mock exam, on Azure Static Web Apps. |
| [capstone-quiz-backend](https://github.com/Melvin-Simplon/capstone-quiz-backend) | Spring Boot 3.5 REST API (Java 21) with PostgreSQL, a Redis cache and result export to Blob Storage. |
| [capstone-quiz-infrastructure](https://github.com/Melvin-Simplon/capstone-quiz-infrastructure) | Terraform infrastructure for the quiz app: private network, PostgreSQL, Redis, Key Vault, App Service, applied by pipeline through OIDC. |

## Kubernetes

Local clusters with Kind, then managed clusters on AKS.

| Project | What it does |
| --- | --- |
| [k8s-kind-getting-started](https://github.com/Melvin-Simplon/k8s-kind-getting-started) | First steps with a local Kind cluster: nginx across 3 replicas, exposed to the host through a Service. |
| [k8s-go-microservices](https://github.com/Melvin-Simplon/k8s-go-microservices) | Three Go microservices (gateway, books, movies) from a single image, only the gateway exposed through a LoadBalancer. |
| [k8s-resource-limits-quotas](https://github.com/Melvin-Simplon/k8s-resource-limits-quotas) | The same microservices under CPU and memory governance: per-container requests and limits, plus a LimitRange and a ResourceQuota. |
| [k8s-ha-multi-zone](https://github.com/Melvin-Simplon/k8s-ha-multi-zone) | A 9-node Kind cluster spanning 3 zones. Strict anti-affinity, rolling updates and probes, stress-tested with Siege during simulated zone failures. |
| [k8s-velero-minio-backup](https://github.com/Melvin-Simplon/k8s-velero-minio-backup) | Backup and restore on a local cluster with Velero, storing backups in MinIO deployed inside Kind. |
| [aks-gitlab-ci-microservices](https://github.com/Melvin-Simplon/aks-gitlab-ci-microservices) | Three Go microservices built into one distroless image and pushed to Azure Container Registry by GitLab CI. Secretless through OIDC. |
| [aks-helm-gitlab-cd](https://github.com/Melvin-Simplon/aks-helm-gitlab-cd) | Helm chart and GitLab CD pipeline deploying those microservices on AKS, load balancer restricted to a single CIDR. |
| [aks-mongodb-azure-files](https://github.com/Melvin-Simplon/aks-mongodb-azure-files) | MongoDB on AKS backed by Azure Files NFS persistent storage. |
| [aks-velero-azure-backup](https://github.com/Melvin-Simplon/aks-velero-azure-backup) | Velero on managed AKS with backups in Azure Blob Storage. Terraform-described, authenticated through Workload Identity, no access key stored. |

## Azure

| Project | What it does |
| --- | --- |
| [azure-compute-comparison](https://github.com/Melvin-Simplon/azure-compute-comparison) | Evaluation of three Azure compute platforms for a company's future API. |
| [azure-compute-bicep](https://github.com/Melvin-Simplon/azure-compute-bicep) | Compute resources as code with Bicep: Linux VM, autoscaling scale set behind a load balancer, App Service with a staging slot, container group. |
| [azure-network-hardening](https://github.com/Melvin-Simplon/azure-network-hardening) | Design, deploy and secure an isolated network architecture. |
| [azure-blob-storage-cli](https://github.com/Melvin-Simplon/azure-blob-storage-cli) | Blob storage driven by the az CLI: private and public containers, SAS URLs, redundancy. |
| [azure-files-smb-secure](https://github.com/Melvin-Simplon/azure-files-smb-secure) | Azure Files share over SMB restricted to a single IP and protected by Azure Backup, provisioned with Terraform. |
| [azure-terraform-migration](https://github.com/Melvin-Simplon/azure-terraform-migration) | Recreating an az CLI infrastructure as Terraform code for versioned, automated management. |
| [azure-container-apps-oidc-cd](https://github.com/Melvin-Simplon/azure-container-apps-oidc-cd) | Continuous deployment of a Flask app to Container Apps through GitLab CI, authenticated with OIDC and no stored secret. |
| [azure-observability-terraform](https://github.com/Melvin-Simplon/azure-observability-terraform) | Full observability stack as Terraform modules: Log Analytics, Application Insights, alerts, availability tests, workbooks. |
| [azure-prometheus-grafana](https://github.com/Melvin-Simplon/azure-prometheus-grafana) | App Insights traces plus managed Prometheus metrics, unified in one Grafana dashboard with email alerts. |
| [azure-logging-api-gitlab-ci](https://github.com/Melvin-Simplon/azure-logging-api-gitlab-ci) | Containerized logging API deployed fully as code with Terraform and GitLab CI/CD. |

## Containers, infrastructure and Git

| Project | What it does |
| --- | --- |
| [docker-go-multistage](https://github.com/Melvin-Simplon/docker-go-multistage) | A Go web service packaged with a multi-stage Dockerfile, exposing a /healthz endpoint wired to the container healthcheck. |
| [docker-go-api-haproxy](https://github.com/Melvin-Simplon/docker-go-api-haproxy) | A Go (Gin) REST API backed by MongoDB, scaled across replicas behind an HAProxy load balancer. |
| [terraform-gitlab-managed-state](https://github.com/Melvin-Simplon/terraform-gitlab-managed-state) | Terraform http backend on GitLab Managed State: importing a hand-created resource, state migration, locking. |
| [openstack-devstack-on-azure](https://github.com/Melvin-Simplon/openstack-devstack-on-azure) | Self-hosted OpenStack on Azure. Terraform builds the host, Ansible installs DevStack, one command demos it end to end. |
| [git-pull-request-workflow](https://github.com/Melvin-Simplon/git-pull-request-workflow) | Git exercise on pull requests and collaboration workflows. |
| [github-actions-basics](https://github.com/Melvin-Simplon/github-actions-basics) | Hands-on GitHub exercises: repositories, branches, pull requests, Actions. |
