<h1 align="center">Nicholas Paolillo</h1>

<p align="center">
  <b>Senior Platform Engineer</b> · Go · Kubernetes · Helm · Supply Chain Security<br>
  Building release infrastructure for <a href="https://github.com/rancher">Rancher</a> at <a href="https://www.suse.com">SUSE</a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/nicholas-software-engineer"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://github.com/nicholasSUSE"><img src="https://img.shields.io/badge/Work_profile-nicholasSUSE-30BA78?style=flat-square&logo=github&logoColor=white" alt="Work GitHub"></a>
  <img src="https://img.shields.io/badge/Based_in-Brazil_(UTC--3)-555?style=flat-square" alt="Location">
</p>

---

### About

Platform engineer with 9+ years in software, the last 3+ at SUSE working on Go and Kubernetes.
I maintain the Helm chart release infrastructure behind Rancher, a platform that manages fleets of
Kubernetes clusters from a single control plane, and whose charts run in production at a majority of Fortune 500 companies.

I care about boring, predictable releases, tooling developers actually want to use, and keeping
every artifact traceable from source to registry.

### Highlights

- **Principal maintainer** of Rancher's chart release infrastructure: 40+ charts across concurrent release branches, 3M+ daily requests
- **67% faster releases** (3 days → 1 day) through Go release automation
- **80% faster validation** (25 → 5 min) with bounded Go worker pools — [rancher/charts-build-scripts#265](https://github.com/rancher/charts-build-scripts/pull/265)
- **Supply chain hardening**: cosign / SLSA verification and OCI artifact isolation between community and commercial channels
- **1,900+ merged public PRs** across the Rancher ecosystem, plus upstream fixes to [go-git](https://github.com/go-git/go-git/pulls?q=is%3Apr+is%3Amerged+author%3AnicholasSUSE)

### Open source at work

| Repository | What I do |
|---|---|
| [rancher/charts](https://github.com/rancher/charts/pulls?q=is%3Apr+is%3Amerged+author%3AnicholasSUSE) | Release management, GitOps propagation of CI tooling across release branches |
| [rancher/charts-build-scripts](https://github.com/rancher/charts-build-scripts/pulls?q=is%3Apr+is%3Amerged+author%3AnicholasSUSE) | Maintainer of the Go CLI that builds and releases every Rancher chart |
| [rancher/rancher](https://github.com/rancher/rancher/pulls?q=is%3Apr+is%3Amerged+author%3AnicholasSUSE) | catalogv2 (Rancher's Helm engine) and release wiring between Rancher and its charts |
| [rancherlabs/slsactl](https://github.com/rancherlabs/slsactl/pulls?q=is%3Apr+is%3Amerged+author%3AnicholasSUSE) | Supply chain tooling: copying images with their cosign signatures |
| [rancher/terraform-provider-rancher2](https://github.com/rancher/terraform-provider-rancher2/pull/1265) | Per-app private registry support for `rancher2_app_v2` |

### Personal projects

| Project | Description |
|---|---|
| [homelab](https://github.com/go-nick/homelab) | GitOps-managed k3s cluster: FluxCD, base/staging promotion, Prometheus/Grafana, Cloudflare Tunnel ingress |
| [nixos-flake](https://github.com/go-nick/nixos-flake) | Declarative, reproducible NixOS for the homelab bare metal: flake-based, multi-host, secrets via SOPS/age |
| [azure-terraform-aks-lab](https://github.com/go-nick/azure-terraform-aks-lab) | Terraform + Azure + AKS labs, each an isolated project with its own state and secrets |
| [helm-kubernetes-api-cli-manager](https://github.com/go-nick/helm-kubernetes-api-cli-manager) | Go API server and CLI managing Helm releases through a Kubernetes client abstraction |

### Tech stack

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)
![K3s](https://img.shields.io/badge/K3s-FFC61C?style=flat-square&logo=k3s&logoColor=black)
![Rancher](https://img.shields.io/badge/Rancher-0075A8?style=flat-square&logo=rancher&logoColor=white)
![FluxCD](https://img.shields.io/badge/FluxCD-5468FF?style=flat-square&logo=flux&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)
![NixOS](https://img.shields.io/badge/NixOS-5277C3?style=flat-square&logo=nixos&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)

### Currently

- Shipping monthly Rancher chart releases across distributed teams
- Running and extending my homelab with GitOps
- Deepening Kubernetes, cloud and infrastructure work through KubeCraft
