# shared-assets

Centralised templates and tooling for ModuLix repositories (governance, CI/CD, Renovate, pre-commit, helper scripts).

## Layout

- `default/` – cross-cutting governance + release tooling (CoC, contributing, security, agent, semantic-release, baseline Renovate).
- `ansible-collection/base/` – lint/config, devtools scripts, and CI templates for Ansible collections.
- `ansible-inventory/base/` – starter ignores/config/license for inventory-only repos.
- `container/` – Dockerfile template, pre-commit, Renovate, and CI workflow for container images.
