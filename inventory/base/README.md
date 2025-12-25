# Inventory template

Use this template when bootstrapping internal Ansible inventory repositories.

Includes:
- `.gitignore` tuned for inventories (no keys/secrets, IDE folders, retries/logs).
- `ansible.cfg` with YAML output, disabled host key checking, and no retry files.
- `LICENSE` (Apache-2.0) to satisfy standard verification workflows.

Usage:
- Copy the contents of this folder into a new inventory repo.
- Add your inventory under `inventories/<name>/`, group_vars/host_vars, and docs.
- Keep secrets out of git; prefer environment variables, vault, or sops-managed files kept outside the repo.
