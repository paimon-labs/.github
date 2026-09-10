# Security Policy

## Reporting a vulnerability

If you discover a security vulnerability in any Paimon Labs repository, please **do not** open a public GitHub issue.

Instead, report it privately via GitHub's [private vulnerability reporting](https://docs.github.com/en/code-security/security-advisories/guidance-on-reporting-and-writing/privately-reporting-a-security-vulnerability) feature on the affected repo (Security tab → Report a vulnerability), or contact the maintainer directly.

Please include:
- A description of the vulnerability and its potential impact
- Steps to reproduce it
- Any relevant logs, PoC code, or screenshots

We'll acknowledge reports as quickly as possible and keep you updated as the issue is investigated and fixed.

## Scope

PAIMON is self-hosted software: each deployment supplies its own credentials, database, memory, and RAGs. Vulnerabilities in the **source code/framework** (auth flow, permission scopes, sandboxing, credential handling patterns) are in scope. Misconfiguration of an individual, self-hosted deployment is not something we can act on directly, but reports are still welcome for documentation improvements.

## Supported versions

As a pre-1.0 personal project, only the latest commit on `main` of each repo is supported. There is no LTS/backport policy at this stage.
