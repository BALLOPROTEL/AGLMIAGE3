# Security Policy

## Supported versions

This repository is a small Java/JavaFX project. Security fixes are applied to the default branch.

## Reporting a vulnerability

Do not open a public issue containing credentials, private keys, tokens, passwords, personal data, or exploit details.

If you discover a vulnerability:

1. Revoke or rotate any exposed credential immediately.
2. Remove the secret from the current branch and from Git history if it was committed.
3. Report the issue privately to the repository owner with the affected file, impact, and reproduction steps.

## Repository hygiene

- Never commit `.env` files, private keys, keystores, access tokens, or passwords.
- Keep generated build artifacts out of Git.
- Review third-party dependencies before introducing them.
- Prefer pull requests and branch protection for changes to the default branch.
