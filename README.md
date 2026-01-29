# homelab

This repository contains deployment workflows and templates for deploying web applications to a homelab infrastructure (Traefik + Cloudflare).

Primary artifact:

- homelab-deployment — One-Shot Deployment Workflow (automated pre-flight validation, build, deploy, verification). See the full workflow in the homelab-deployment file in this repository:

  https://github.com/angus-gair/homelab/blob/main/homelab-deployment

Usage:

- Read the `homelab-deployment` file for the recommended One-Shot deployment steps, Dockerfile and docker-compose templates, and troubleshooting guidance.
- The workflow describes validation checks (package.json, Dockerfile, network, docker-compose), build and deploy steps, Traefik verification, and Cloudflare DNS/cache guidance.

If you are contributing or running deployments from this repo, follow the `homelab-deployment` workflow as the authoritative guide.