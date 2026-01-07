# AWX Proxmox EE

This repo contains:
- Ansible playbooks to manage Proxmox
- Execution Environment definition to run in AWX with:
  - community.general collection
  - proxmoxer + requests python libs

## Build EE (local)
Requires ansible-builder + docker/podman.

```bash
ansible-builder build -t awx-ee-proxmox:1.0
