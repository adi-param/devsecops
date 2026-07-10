# DevSecOps

Notes and practical write-ups on securing the software delivery lifecycle: CI/CD pipeline hardening, software supply chain security, secrets management, and shipping safely.

The goal is to keep hands-on, incident-driven security knowledge for build and delivery systems easy to find, connect, and expand over time.

## Structure

```text
docs/
└── cicd-hardening/
```

## Sections

### CI/CD Hardening

Protecting build and delivery pipelines from compromise, drawn from real incidents.

Examples:

- Pinning actions and images (SHA and digest, not tags)
- Least-privilege pipeline permissions and scoped tokens
- OIDC and short-lived credentials over static secrets
- Ephemeral runners and egress control
- Rotation and recovery playbooks after a supply chain attack

## Publishing

Markdown files here opt in to publishing on [adi-blog](https://adi-param.github.io/adi-blog/) via `blog.publish: true` frontmatter. This repo is registered as a source in `adi-blog/sources.yml`.
