# GilmanLab GitOps

This repository holds the GitOps definitions and desired-state automation for
the GilmanLab homelab.

The repository baseline is intentionally thin right now. Moon-based CI and
GitHub repository automation are in place so new Argo CD apps, manifests, and
sync flows can land without re-scaffolding the repo.

## Quick Start

Prerequisites:

- `moon` 2.x

Validate the current repository baseline:

```sh
moon ci --summary minimal
```

Run the root check target directly:

```sh
moon run :check
```

## Support

- Questions and design discussion: GitHub Discussions
- Non-security bugs: GitHub Issues
- Vulnerabilities: follow [SECURITY.md](SECURITY.md)

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md).
