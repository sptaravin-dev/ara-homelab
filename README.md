# ara-homelab
A GitOps-driven Kubernetes homelab infrastructure repository for testing operators, ingress controllers, service meshes, and self-hosted apps — fully automated with Helm, Argo CD, and K3d.

## 📁 Folder Structure
```md
ara-homelab/
├── .devcontainer/
│   ├── devcontainer.json
│   ├── Dockerfile         # optional – customize the base image
│   └── postCreate.sh      # optional – run post-setup steps like installing deps
├── ansible/
│   ├── prereqs.yml
│   ├── inventory
│   ├── roles/
│   └── ansible.cfg
├── clusters/
│   ├── nea1/
│   │   ├── k3d-config.yaml
│   │   └── manifests/
│   ├── usw1/
│   │   ├── k3d-config.yaml
│   │   └── manifests/
│   └── Makefile
├── scripts/
│   └── install-ansible.sh
├── Makefile
├── README.md
└── .gitignore
```
