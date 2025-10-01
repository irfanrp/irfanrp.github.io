# Irfan RP — DevOps & SRE Portfolio

This repository contains my personal DevOps portfolio showcasing infrastructure, automation, and reliability engineering work. The site is a static HTML/CSS/JS site intended to present key projects, skills, and contact information.

## What you'll find here

- A concise DevOps-focused portfolio website (`index.html`) highlighting cloud architecture, CI/CD, IaC, Kubernetes, and observability projects.
- Reusable static site (no build system required) so you can host on GitHub Pages or any static host.
- Sample project case studies and links to repos (replace placeholders with your real repos).

## DevOps-Focused Highlights

- Infrastructure as Code (Terraform) modules for provisioning VPC, EKS/managed clusters, and RDS.
- GitOps workflows using ArgoCD and Kustomize for multi-cluster deployments.
- CI/CD pipelines implemented with GitHub Actions and Jenkins for secure plan/apply and canary releases.
- Containerization and orchestration: Docker & Kubernetes (Helm, Operators).
- Observability: Prometheus, Grafana, Loki and alerting routed to Slack/PagerDuty.
- Security & Compliance: IAM, secrets management (Vault/Secrets Manager) and automated scanning in pipelines.

## Quick Start (Preview Locally)

Clone the repo and start a simple static server (Python shown here):

```bash
git clone https://github.com/irfanrp/irfanrp.github.io.git
cd irfanrp.github.io
python3 -m http.server 8000
# open http://localhost:8000 in your browser
```

## Make it yours

1. Replace placeholder project links in `index.html` with real GitHub repo URLs or case studies.
2. Update contact details in the Contact section.
3. Add additional project pages or write detailed case studies and link them from the Projects section.

## Project Structure

```
irfanrp.github.io/
├── index.html          # DevOps-focused portfolio
├── styles.css          # Styles
├── script.js           # Interactions and small utilities
├── README.md           # This file
├── CHANGELOG.md
└── LICENSE
```

## Recommended next steps (optional)

- Add a `projects/` folder with detailed case studies and diagrams.
- Add badges or links to pipelines (e.g., GitHub Actions status) for each showcased repo.
- Integrate a contact backend (Formspree, Netlify Forms) or link to Calendly for booking.

## Contact

Prefer email or LinkedIn for professional inquiries. See the Contact section on the site.

---

If you want, I can now:

1. Replace all placeholder project links with sample GitHub URLs or your repos.
2. Add a `projects/` folder and create one detailed case study page (IaC or GitOps) with diagrams.
3. Add a small script to automatically list your public GitHub repos on the Projects section (requires a GitHub username).

Pilih opsi yang Anda mau dan saya akan lanjutkan implementasinya.