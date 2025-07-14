# Homelab

This is my k8s homelab running on a mini PC at home. It’s a work in progress as I build and improve it.

## Current setup

- OS: Debian

- K3s Kubernetes cluster

- Port forwarding + Cloudflare DNS

- Cert-manager + Let's Encrypt for certificates

- All services are deployed declaratively using ArgoCD (Infrastructure as Code).

- Uptime Kuma is hosted and monitors service uptime. ([status page](https://status.jg1g.com/status/homelab))

- Authentik is deployed as a Single Sign-On (SSO) provider (not yet integrated with other services).

- First App: [httpbin](https://httpbin.jg1g.com/)

  [![](https://status.jg1g.com/api/badge/3/status)](#)[![](https://status.jg1g.com/api/badge/3/uptime/168)](#)

