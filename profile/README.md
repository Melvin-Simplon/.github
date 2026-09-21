<br/>

<h1 align="center">Melvin at Simplon.co</h1>

<p align="center">
  <i>Cloud &amp; DevSecOps training at <a href="https://www.simplon.co/">Simplon.co</a></i>
</p>

<br/>

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=azure,terraform,kubernetes,docker,gitlab,githubactions,ansible,golang,java,python,bash,linux&perline=12" alt="Tech stack" />
  </a>
</p>

<br/>

<p align="center">
  <a href="https://github.com/WhiteMuush"><img src="https://img.shields.io/badge/Personal_account-FF6200?style=for-the-badge&logo=github&logoColor=white" alt="Personal account" /></a>
</p>

<br/>
<br/>

Trained in Toulouse, specialising in Azure. This organization gathers every project built along the way: four capstone projects and
twenty-six hands-on labs, grouped below by the skill they demonstrate rather than
by the tool they happen to use.

<br/>

---

<br/>

## Capstone projects

End-to-end work, specified and delivered alone, closing each phase of the programme.

| Project | Stack | What it demonstrates |
| --- | --- | --- |
| [capstone-aks-gitops-platform](https://github.com/Melvin-Simplon/capstone-aks-gitops-platform) | <img src="https://skillicons.dev/icons?i=azure,terraform,kubernetes,gitlab" height="22" /> | A full Azure platform: Entra ID identity access, AKS with remote Velero backups, and zero credentials stored in Git or Kubernetes. |
| [capstone-quiz-frontend](https://github.com/Melvin-Simplon/capstone-quiz-frontend) | <img src="https://skillicons.dev/icons?i=azure,angular,typescript" height="22" /> | Angular 22 app for revising Azure certifications, by module or mock exam, on Static Web Apps. |
| [capstone-quiz-backend](https://github.com/Melvin-Simplon/capstone-quiz-backend) | <img src="https://skillicons.dev/icons?i=azure,java,spring,postgresql,redis" height="22" /> | Spring Boot 3.5 REST API on Java 21, with a Redis cache and result export to Blob Storage. |
| [capstone-quiz-infrastructure](https://github.com/Melvin-Simplon/capstone-quiz-infrastructure) | <img src="https://skillicons.dev/icons?i=azure,terraform" height="22" /> | Private network, PostgreSQL, Redis, Key Vault and App Service, applied by pipeline through OIDC. |
<br/>

---

<br/>

## Infrastructure as Code

Describing infrastructure in version-controlled code rather than clicking through a portal.

| Project | Stack | What it demonstrates |
| --- | --- | --- |
| [azure-compute-comparison](https://github.com/Melvin-Simplon/azure-compute-comparison) | <img src="https://skillicons.dev/icons?i=azure" height="22" /> | Choosing between three Azure compute platforms for a company's future API, with the trade-offs written down. |
| [azure-compute-bicep](https://github.com/Melvin-Simplon/azure-compute-bicep) | <img src="https://skillicons.dev/icons?i=azure,bash" height="22" /> | Linux VM, autoscaling scale set behind a load balancer, App Service with a staging slot, deployed as deployment stacks. |
| [azure-terraform-migration](https://github.com/Melvin-Simplon/azure-terraform-migration) | <img src="https://skillicons.dev/icons?i=azure,terraform" height="22" /> | Rebuilding a hand-made az CLI infrastructure as Terraform code, for versioned and repeatable management. |
| [azure-network-hardening](https://github.com/Melvin-Simplon/azure-network-hardening) | <img src="https://skillicons.dev/icons?i=azure" height="22" /> | Designing and securing an isolated network architecture, segment by segment. |
| [azure-files-smb-secure](https://github.com/Melvin-Simplon/azure-files-smb-secure) | <img src="https://skillicons.dev/icons?i=azure,terraform" height="22" /> | An SMB file share restricted to a single IP and protected by Azure Backup, operated through a Makefile. |
| [azure-blob-storage-cli](https://github.com/Melvin-Simplon/azure-blob-storage-cli) | <img src="https://skillicons.dev/icons?i=azure,bash" height="22" /> | Private and public containers, SAS URLs and redundancy options, driven entirely from the az CLI. |
| [terraform-gitlab-managed-state](https://github.com/Melvin-Simplon/terraform-gitlab-managed-state) | <img src="https://skillicons.dev/icons?i=azure,terraform,gitlab" height="22" /> | Importing an existing resource into state, migrating the backend, and proving that locking works. |
| [openstack-devstack-on-azure](https://github.com/Melvin-Simplon/openstack-devstack-on-azure) | <img src="https://skillicons.dev/icons?i=azure,openstack,terraform,ansible" height="22" /> | A self-hosted cloud: Terraform builds the host, Ansible installs DevStack, one command demos it end to end. |
<br/>

---

<br/>

## CI/CD and automated delivery

Getting code from a commit to a running environment without a human holding a secret.

| Project | Stack | What it demonstrates |
| --- | --- | --- |
| [git-pull-request-workflow](https://github.com/Melvin-Simplon/git-pull-request-workflow) | <img src="https://skillicons.dev/icons?i=github,git" height="22" /> | Branching, pull requests and review workflow as a team would run them. |
| [github-actions-basics](https://github.com/Melvin-Simplon/github-actions-basics) | <img src="https://skillicons.dev/icons?i=github,githubactions" height="22" /> | First pipelines: triggers, jobs and collaboration workflows on GitHub. |
| [azure-container-apps-oidc-cd](https://github.com/Melvin-Simplon/azure-container-apps-oidc-cd) | <img src="https://skillicons.dev/icons?i=azure,gitlab,python,flask" height="22" /> | Continuous deployment of a Flask app to Container Apps, authenticated with OIDC and no stored secret. |
| [aks-gitlab-ci-microservices](https://github.com/Melvin-Simplon/aks-gitlab-ci-microservices) | <img src="https://skillicons.dev/icons?i=azure,kubernetes,gitlab,golang" height="22" /> | Three Go services built into one distroless image, pushed to Azure Container Registry, one tag per commit. |
| [aks-helm-gitlab-cd](https://github.com/Melvin-Simplon/aks-helm-gitlab-cd) | <img src="https://skillicons.dev/icons?i=azure,kubernetes,gitlab" height="22" /> <img src="https://cdn.simpleicons.org/helm/0F1689" height="22" /> | The deployment half: a Helm chart shipped to AKS by pipeline, load balancer restricted to a single CIDR. |
| [azure-logging-api-gitlab-ci](https://github.com/Melvin-Simplon/azure-logging-api-gitlab-ci) | <img src="https://skillicons.dev/icons?i=azure,terraform,docker,gitlab" height="22" /> | A containerised logging API delivered fully as code, infrastructure and application in the same pipeline. |
<br/>

---

<br/>

## Reliability and disaster recovery

Surviving a node loss, a zone loss, or a bad afternoon.

| Project | Stack | What it demonstrates |
| --- | --- | --- |
| [k8s-ha-multi-zone](https://github.com/Melvin-Simplon/k8s-ha-multi-zone) | <img src="https://skillicons.dev/icons?i=kubernetes,golang" height="22" /> | Nine nodes across three zones, strict anti-affinity and rolling updates, stress-tested with Siege during simulated zone failures. |
| [k8s-resource-limits-quotas](https://github.com/Melvin-Simplon/k8s-resource-limits-quotas) | <img src="https://skillicons.dev/icons?i=kubernetes,golang" height="22" /> | Per-container requests and limits, plus a LimitRange and a ResourceQuota to cap namespace consumption. |
| [k8s-velero-minio-backup](https://github.com/Melvin-Simplon/k8s-velero-minio-backup) | <img src="https://skillicons.dev/icons?i=kubernetes" height="22" /> <img src="https://cdn.simpleicons.org/minio/C72E49" height="22" /> | Backup and restore with Velero, storing the backups in MinIO deployed inside the cluster. |
| [aks-velero-azure-backup](https://github.com/Melvin-Simplon/aks-velero-azure-backup) | <img src="https://skillicons.dev/icons?i=azure,terraform,kubernetes" height="22" /> | The same discipline on managed AKS: backups in Blob Storage, Velero authenticated through Workload Identity. |
<br/>

---

<br/>

## Observability

Knowing what the system is doing before a user tells you.

| Project | Stack | What it demonstrates |
| --- | --- | --- |
| [azure-observability-terraform](https://github.com/Melvin-Simplon/azure-observability-terraform) | <img src="https://skillicons.dev/icons?i=azure,terraform,python" height="22" /> | Log Analytics, Application Insights, alerts, availability tests and workbooks, all shipped as Terraform modules. |
| [azure-prometheus-grafana](https://github.com/Melvin-Simplon/azure-prometheus-grafana) | <img src="https://skillicons.dev/icons?i=azure,terraform,prometheus,grafana" height="22" /> | App Insights traces and managed Prometheus metrics unified in one Grafana dashboard, with email alerting. |
| [datadog-observability-certifications](https://github.com/Melvin-Simplon/datadog-observability-certifications) | <img src="https://raw.githubusercontent.com/Melvin-Simplon/.github/main/profile/assets/datadog.svg" height="32" /> | Course completion certificates from the Datadog Learning Center, kept as proof of the observability training followed. |
<br/>

---

<br/>

## Containers and orchestration

Packaging an application, then running it across a cluster.

| Project | Stack | What it demonstrates |
| --- | --- | --- |
| [docker-go-multistage](https://github.com/Melvin-Simplon/docker-go-multistage) | <img src="https://skillicons.dev/icons?i=docker,golang" height="22" /> | A multi-stage Dockerfile and a /healthz endpoint wired to the container healthcheck. |
| [docker-go-api-haproxy](https://github.com/Melvin-Simplon/docker-go-api-haproxy) | <img src="https://skillicons.dev/icons?i=docker,golang,mongodb" height="22" /> | A Gin REST API on MongoDB, scaled across replicas behind an HAProxy load balancer. |
| [k8s-kind-getting-started](https://github.com/Melvin-Simplon/k8s-kind-getting-started) | <img src="https://skillicons.dev/icons?i=kubernetes,nginx" height="22" /> | A first local cluster: three nginx replicas exposed to the host through a Service. |
| [k8s-go-microservices](https://github.com/Melvin-Simplon/k8s-go-microservices) | <img src="https://skillicons.dev/icons?i=kubernetes,golang" height="22" /> | Gateway, books and movies services from a single image, only the gateway exposed. |
| [aks-mongodb-azure-files](https://github.com/Melvin-Simplon/aks-mongodb-azure-files) | <img src="https://skillicons.dev/icons?i=azure,kubernetes,mongodb" height="22" /> | Stateful workloads on AKS, backed by Azure Files NFS persistent storage. |
| [aks-cluster-access-hardening](https://github.com/Melvin-Simplon/aks-cluster-access-hardening) | <img src="https://skillicons.dev/icons?i=azure,kubernetes" height="22" /> | Entra ID groups mapped to cluster roles, an API server locked to one IP range, and namespace quotas on a cluster that started out wide open. |
