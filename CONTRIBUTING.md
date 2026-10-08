# Contributing to `cpintl-org`

Thank you for helping maintain the `cpintl-org` GitHub organization.

This organization is maintained by a non-coder Health Program Manager. Contributions must be understandable, reversible, and safe for public and private repositories.

## Before you change anything

1. Confirm the exact repository and file you intend to change.
2. Read that repository's `README.md`, `AGENTS.md`, and `SECURITY.md` when present.
3. Use a short lowercase kebab-case branch name such as `docs/improve-index` or `chore/validate-links`.
4. Do not add a new provider, paid service, Google Workspace connection, or external secret without explicit approval.
5. Never commit passwords, API keys, tokens, private keys, personal data, patient data, or confidential exports.

## Preferred change flow

1. Describe the goal in plain language.
2. Make the smallest useful change.
3. Run the repository's documented checks.
4. Review the changed files and the rendered Markdown.
5. Open a pull request unless this is controlled maintenance by the repository owner.
6. Explain what changed, how it was checked, and what remains for a human to decide.

## Naming

For new portable names, use lowercase ASCII kebab-case:

- Repository: `short-purpose`
- Directory: `short-purpose`
- File: `short-purpose.extension`
- Branch: `docs/short-purpose`, `feat/short-purpose`, or `chore/short-purpose`
- Environment variable: `UPPER_SNAKE_CASE`
- JSON field: `lowerCamelCase`

Keep provider-required names such as `.github`, `README.md`, `AGENTS.md`, and `SKILL.md` exactly as required by the provider or tool.

## Pull request checklist

- [ ] The title says what changed, in plain language.
- [ ] The scope is limited to the stated purpose.
- [ ] No secret, personal data, patient-identifiable data, or confidential export was added.
- [ ] Links and paths were checked.
- [ ] Repository validation passed, or the failure is explained.
- [ ] Any consequential action is clearly marked for human review.
- [ ] The change does not assume a provider is free, private, available, or suitable for sensitive data.

## Human approval is required for

- Publishing or sharing restricted material.
- Changing access, ownership, billing, branch protection, or security settings.
- Deleting repositories, data, releases, or collaborators.
- Deploying a Google Workspace bridge or enabling write mode.
- Processing patient-level, clinical, safeguarding, or beneficiary-identifiable data.

## Questions

Open a discussion or contact the repository owner through the normal GitHub workflow. Do not include sensitive information in an issue or pull request.
