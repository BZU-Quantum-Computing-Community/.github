# .github

Organization-wide configuration repository for **BZU Quantum Computing Community**.

This repository defines the defaults inherited by every repository in the organization, unless a repository overrides them locally:

| File | Purpose |
|---|---|
| `profile/README.md` | Rendered as the organization's public homepage |
| `ISSUE_TEMPLATE/` | Default issue templates for repositories without their own |
| `PULL_REQUEST_TEMPLATE.md` | Default pull request template |
| `CONTRIBUTING.md` | Organization-wide contribution workflow |
| `CODE_OF_CONDUCT.md` | Organization-wide community standards |

## Rationale

Rather than duplicating governance files across six or more repositories, GitHub allows these to be defined once, centrally, and inherited automatically. This keeps our standards consistent as the organization grows and reduces maintenance overhead.

## Ownership

Changes to this repository affect the entire organization's default experience and are restricted to `@leadership`. Individual teams requiring repository-specific templates should add a local `.github/` folder within their own repository — this will take precedence over the organization defaults defined here.
