# Organization-wide agent guidance

These instructions apply to work across `cpintl-org` repositories. Repository-local `AGENTS.md` files are more specific and take precedence.

## Work style

- Write for Mohammad Ariful ISLAM, a non-coder Health Program Manager.
- Use plain language and explain unavoidable commands in one sentence.
- Inspect before editing; make small, reversible changes.
- Keep `v0.1.x` artifacts clearly marked as early-stage and provider-neutral.
- Do not add Google Workspace integrations at this stage.
- Do not add paid services, billing, or new providers without explicit approval.

## Safety

- Never invent IDs, URLs, quotas, standards claims, or provider capabilities.
- Never commit secrets, patient-identifiable data, clinical data, safeguarding data, or confidential exports.
- Preserve provider-required names such as `.github`, `README.md`, `AGENTS.md`, and `SKILL.md`.
- Ask before changing access, ownership, billing, security controls, branch protection, or published content.
- Keep a manual/no-AI path for every provider integration.

## Naming

Use lowercase ASCII kebab-case for new repositories, directories, portable filenames, and slugs; `UPPER_SNAKE_CASE` for environment variables; and `lowerCamelCase` for new JSON fields. Preserve opaque provider IDs exactly as returned.

## Completion

Before presenting a change:

1. State the repository and files changed.
2. Run the repository's checks or clearly report why a check could not run.
3. Review `git diff --check`.
4. Explain the result in plain language and identify any remaining human decision.
