# Security policy

## Scope

This policy applies to the repositories maintained by `cpintl-org`.

The repositories are not a system of record, secret manager, clinical system, or approved storage location for beneficiary-identifiable information.

## Never commit

- Passwords, API keys, access tokens, private keys, or OAuth credentials.
- Patient-identifiable, clinical, safeguarding, or beneficiary-level data.
- Confidential exports, database dumps, or restricted internal documents.
- Personal information in filenames, issues, prompts, logs, examples, or test fixtures.

Use approved access-controlled systems and secret stores instead. Do not paste a secret into a public issue or pull request while reporting a problem.

## Report a vulnerability

If a report contains sensitive information, do not open a public issue. Contact the repository owner through a private GitHub channel and provide only the minimum necessary details.

Include:

- The affected repository and file or workflow.
- A short description of the risk.
- Safe reproduction steps using synthetic data only.
- The likely impact and a suggested mitigation, if known.

If a secret was exposed, revoke or rotate it immediately through the provider, then report the exposure. Removing the file from the latest commit does not make an exposed secret safe.

## Response principles

Reports are handled privately and in good faith. The maintainer will assess scope, protect affected data, rotate credentials when applicable, record the fix, and publish only a sanitized summary when appropriate.
