# 221B-doc
Global documentation about the server

```mermaid
graph TD
    Proxmox[Proxmox Host] --> DevOpsVM[VM: devops-server 🛠️]
    Proxmox --> VaultVM[VM: vault 🛡️]
    Proxmox --> K3sDev[VM: k3s-dev 🚀]
    Proxmox --> K3sProd[VM: k3s-prod 🚀]
    Proxmox --> MonitoringVM[VM: monitoring 📈]
```
