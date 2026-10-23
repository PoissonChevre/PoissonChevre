# Homelab

My playground for breaking things on purpose and fixing them properly. I document every step so that anything can be rebuilt from scratch. Updated as it evolves.

[Back to profile](https://github.com/PoissonChevre)

## Architecture

<!-- add a diagram here (draw.io or Excalidraw export) -->

| Role | What runs it |
|---|---|
| Router / firewall | OPNsense |
| Storage | TrueNAS |
| Virtualisation | Proxmox VE |
| Orchestration | Kubernetes cluster on Talos Linux |
| Provisioning | Terraform and Ansible |

## Repositories

| Repository | Content |
|---|---|
| [proxmox](https://github.com/PoissonChevre/proxmox) | VM and container templates built from cloud images with cloud-init |

## Roadmap

- [x] OPNsense router and firewall
- [x] TrueNAS storage
- [x] Proxmox VE
- [x] Kubernetes cluster
- [ ] Provision Proxmox VMs with Terraform
- [ ] Configure hosts with Ansible
- [ ] CI with GitHub Actions: fmt, validate, lint
- [ ] GitOps on the Kubernetes cluster
