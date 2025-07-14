# Homelab

This is my k8s homelab running on a mini PC at home. It’s a work in progress as I build and improve it.

## Current setup

- OS: Debian

- K3s Kubernetes cluster

- Port forwarding + Cloudflare DNS

- Cert-manager + Let's Encrypt for certificates

- First App managed by ArgoCD: [httpbin](https://httpbin.jg1g.com/)
  [![](https://status.jg1g.com/api/badge/3/status)](#)[![](https://status.jg1g.com/api/badge/3/uptime/168)](#)

- Tailscale integration for secure ArgoCD access
