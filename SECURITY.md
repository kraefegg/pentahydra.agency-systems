# Security Policy

## Supported Versions

| Version | Supported |
| ------- | :-------: |
| latest  | ✅        |

## Reporting Vulnerabilities

Please do not disclose security vulnerabilities publicly. Instead, report them via the following secure channel:

**Encoded Email:** contact@pentahydra.agency

## What to Include

* Type of vulnerability
* affected repository or component
* Steps to reproduce
* Potential impact on engineering pipelines or AI systems
* Your contact information (optional)

## Response Timeline

* Initial response within 5 business days
* Preliminary assessment within 10 business days
* Fix ETA provided after assessment, considering modular architecture components

## Security Best Practices

* All agentic engineering systems maintain explicit provenance and audit trails
* No offensive cybersecurity tools or techniques published in engineering repositories
* API keys, passwords, tokens, and private keys must never be committed
* All AI provider integrations document provider layers and credential management
* pgvector and database integrations follow principle of least privilege
* Edge/IoT device credentials rotated and never persisted in repositories

## Pre-Disclosure

Project maintainers will attempt to fix the vulnerability before public disclosure. A reasonable window of at least 90 days will be given for critical vulnerabilities, depending on severity and complexity across the Agent Runtime, Orchestrator, and Execution Engine components.

## Scope

This policy applies to all repositories within the PentaHydra Agency Systems organization, including agentic engineering, AI systems, data platforms, and infrastructure repositories.

## Credential Management

* All secrets and credentials must be managed via secure environment variables
* No credentials documented in README files, wiki, or inline documentation
* Secret scanning enabled on all repositories
* Token rotation policies enforced for all CI/CD pipelines