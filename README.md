# Tech-Nexus

![Status](https://img.shields.io/badge/Status-Active-success) ![License](https://img.shields.io/badge/License-MIT-blue) ![PRs](https://img.shields.io/badge/PRs-Welcome-brightgreen)

The central convergence point for technical articles, roadmaps, and deep-dives into DevOps, Cloud Architecture, AI/ML, Cybersecurity, and emerging tech trends.

This repository is organized as a knowledge hub where each top-level folder groups focused content and guides. Use this page as the home dashboard to find domains, templates, and contribution guidance.

**Quick Links**

- **Contributing guide:** `CONTRIBUTING.md`
- **Article template:** `TEMPLATES/article_template.md`
- **Repository script:** `scripts/create_structure.sh` (kept locally; ignored by git)
- **.gitignore:** `.gitignore`

**Table of Contents**

- [DevOps & SRE](#devops--sre)
- [Cloud Architecture](#cloud-architecture)
- [Artificial Intelligence & ML](#artificial-intelligence--ml)
- [Cybersecurity](#cybersecurity)
- [Web Development](#web-development)
- [Trends & Analysis](#trends--analysis)
- [How to contribute](#how-to-contribute)
- [Host on GitHub Pages](#host-on-github-pages)

---

## DevOps & SRE

Path: `01-DevOps-Engineering/`

Focus: CI/CD, Kubernetes, Docker, Terraform, Observability, and SRE best practices.

- Browse the folder: `01-DevOps-Engineering/`
- Quick subfolders created: `Docker/`, `Kubernetes/`, `Terraform/`, `CI-CD/`, `Observability/`, `SRE/`

## Cloud Architecture

Path: `02-Cloud-Architecture/`

Focus: Multi-cloud architecture, AWS/Azure/GCP guides, Serverless, Cost optimization, and Cloud security.

- Browse the folder: `02-Cloud-Architecture/`
- Quick subfolders created: `AWS/`, `Azure/`, `GCP/`, `Serverless/`, `Cost-Optimization/`, `Cloud-Security/`

## Artificial Intelligence & ML

Path: `03-Artificial-Intelligence/`

Focus: GenAI, MLOps, Data Engineering, Computer Vision, NLP, Model deployment and practical patterns.

- Browse the folder: `03-Artificial-Intelligence/`
- Quick subfolders created: `GenAI/`, `MLOps/`, `Data-Engineering/`, `Computer-Vision/`, `NLP/`, `Model-Deployment/`

## Cybersecurity

Path: `04-Cybersecurity/`

Focus: DevSecOps, Network security, Application security, Compliance, Incident response and threat modeling.

- Browse the folder: `04-Cybersecurity/`
- Quick subfolders created: `DevSecOps/`, `Network-Security/`, `Application-Security/`, `Compliance/`, `Incident-Response/`, `Threat-Modeling/`

## Web Development

Path: `05-Web-Development/`

Focus: Frontend, backend, performance, accessibility, developer tools and web security best practices.

- Browse the folder: `05-Web-Development/`
- Quick subfolders created: `Frontend/`, `Backend/`, `DevTools/`, `Performance/`, `Accessibility/`, `Web-Security/`

## Trends & Analysis

Path: `99-Trends-and-Analysis/`

Focus: Web3, Edge computing, Quantum, industry reports and future-looking research.

- Browse the folder: `99-Trends-and-Analysis/`
- Quick subfolders created: `Web3/`, `Edge-Computing/`, `Quantum/`, `Industry-Reports/`

---

## How to contribute

1. Fork the repository and create a branch: `git checkout -b topic/your-article-name`
2. Use the article template at `TEMPLATES/article_template.md` for new content
3. Add your `.md` file under the appropriate folder (for example: `01-DevOps-Engineering/Kubernetes/your-article.md`)
4. Commit, push, and open a Pull Request

Frontmatter example (required):

```yaml
---
title: "The Future of Kubernetes"
category: "DevOps"
tags: [k8s, containerization, orchestration]
last_updated: 2025-11-29
---
```

See `CONTRIBUTING.md` for full contribution guidelines.

## Contributing & Guidelines (for authors and maintainers)

This repository is a community knowledge hub. If you want to contribute articles, tutorials, or reference notes, please follow these guidelines to keep the content consistent and discoverable.

Required files and frontmatter
- Use the article template at `TEMPLATES/article_template.md` for new posts.
- Every article must include YAML frontmatter with these required fields:

```yaml
---
title: "Your article title"
category: "<Domain name>"
tags: [tag1, tag2]
last_updated: YYYY-MM-DD
---
```

Where to add content
- Place articles inside the appropriate top-level domain and subfolder (for example: `01-DevOps-Engineering/Kubernetes/your-article.md`).

Writing & style tips
- Keep articles clear, vendor-neutral when possible, and provide source links for claims or commands.
- Include runnable examples, commands, and code blocks where helpful.
- Use headings, short paragraphs, and optional diagrams for complex topics.

Pull request workflow
- Fork the repository and create a branch: `git checkout -b topic/your-article-name`.
- Add your Markdown file, commit, and open a Pull Request against `main`.
- The repository runs automatic checks on PRs to validate frontmatter and formatting. Fix any issues the CI reports and push updates to your branch.

Assets, images and large files
- Keep images under `assets/` and reference them using relative paths (e.g., `assets/images/diagram.png`).
- For large binaries or datasets, use a hosted link and include instructions to fetch them.

Licensing and attribution
- By contributing you agree to license your contribution under this repository's MIT license.
- Attribute external sources and respect third-party licenses. Prefer linking to original docs.

Code of conduct
- Be respectful, constructive, and inclusive in discussions and contributions. Report concerns by opening an issue and tagging a maintainer.

---

