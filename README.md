# Homelab K3s Cluster
## Infrastructure Stack
- **MetalLB**: LoadBalancer 
- **nginx-ingress**: Ingress controller
- **cert-manager**: SSL certificates (Let's Encrypt)
- **Longhorn**: Distributed persistent storage
## Applications
- Pi-Hole
- Vaultwarden
- Ryncthing
- Portainer
## Cluster status
- control plane: k3s-control
- worker node: k3s-worker
- Infrastructure: MetalLB, nginx-ingress, cert-manager, Longhorn
## Setup
See docs/setup.md
