# Contributing to Hephaestus

Thank you for considering a contribution! This document holds the **organization-wide** contribution
rules for `hephaestus-build`. Each repository's own `CONTRIBUTING.md` and `AGENTS.md` govern the
specifics — setup, coding conventions, quality gates, and review process — so read those before
starting work in a repository.

## Maintenance Status

Hephaestus is a research project at the Technical University of Munich, actively developed but
maintained primarily by one person. Issues and pull requests are triaged on a best-effort basis.
Security reports are the exception and get priority — see the [Security Policy](./SECURITY.md) for
how to report vulnerabilities privately.

## Identity Requirements

To maintain a trustworthy and transparent community, **all contributors** must:

- **Use their real full name** in their GitHub profile.
- **Upload an authentic profile picture** — a clear, professional photo. Avoid memojis, avatars, or
  comic-style images.

These requirements apply to both organization members and external contributors. Contributions that
do not adhere to this policy may not be accepted. For full details, see the
[Code of Conduct](./CODE_OF_CONDUCT.md#identity-and-transparency).

## How to Contribute

### Reporting Bugs

- Search the repository's issues first to see if the bug has already been reported.
- If not, open a new issue using the available bug report template.
- Include clear reproduction steps, your environment, and screenshots where applicable.

### Suggesting Enhancements

- Open a feature request issue in the appropriate repository.
- For large or architectural changes, open a discussion first so the direction can be agreed before
  the work is done.

### Reporting Security Issues

Never report a vulnerability through a public issue, discussion, or pull request. Follow the
[Security Policy](./SECURITY.md) instead.

## Contribution Process

### For Members of the Organization

1. **Create a feature branch** directly in the repository, with a descriptive name.
2. **Work on your changes** in that branch, following the conventions in the repository's own
   `CONTRIBUTING.md` and `AGENTS.md`.
3. **Open a pull request** against `main` (or the appropriate base) and fill in the PR template.
4. **Respond to review feedback** and keep your branch up to date.

### For External Contributors

1. **Verify your identity**: ensure your GitHub profile uses your real name and an authentic photo.
2. **Fork the repository** you want to contribute to.
3. **Create a feature branch** in your fork with a descriptive name.
4. **Make your changes**, following the coding standards and conventions defined in the repository.
5. **Open a pull request** from your fork to the upstream repository's `main` branch.
6. **Keep your branch up to date** with the upstream main branch before requesting review.

## Repository Standards

Each repository defines its own conventions — read the relevant guide before starting:

| Repository | Guides |
| ---------- | ------ |
| [Hephaestus](https://github.com/hephaestus-build/Hephaestus) | [`CONTRIBUTING.md`](https://github.com/hephaestus-build/Hephaestus/blob/main/CONTRIBUTING.md) — PR titles, changesets, and process; [`AGENTS.md`](https://github.com/hephaestus-build/Hephaestus/blob/main/AGENTS.md) — quality gates, generated artefacts, and package guides |

General cross-repository expectations:

- Keep pull requests **small and focused** — one concern per PR.
- PR titles follow [Conventional Commits](https://www.conventionalcommits.org/).
- Update documentation when you change behavior, and add or update tests as appropriate.
- Run the repository's quality gates before requesting review.

## Code of Conduct

By contributing, you agree to abide by our [Code of Conduct](./CODE_OF_CONDUCT.md). Please read it
before participating.

---

Hephaestus is developed at the
[Research Group Applied Education Technologies (AET)](https://aet.cit.tum.de), Technical University
of Munich.
