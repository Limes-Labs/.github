# Security Policy

Limes Labs is early, public, and still organizing capability. Security reports are welcome, but sensitive details should not be posted in public issues or pull requests.

## Responsible disclosure

If you believe you have found a vulnerability or sensitive exposure, email hello@limeslabs.eu with the subject line `[security]`.

Please include:

- the affected repository, file, service, or workflow
- a concise description of the issue
- impact and affected users, if known
- minimal reproduction details that do not expose secrets or enable harm
- whether any credentials, private data, model weights, datasets, or institutional information may be involved

## Do not post publicly

Please do not open public issues or pull requests containing:

- secrets, tokens, private keys, credentials, or access links
- exploit chains or weaponized proof-of-concept code
- private institutional correspondence or contact details
- non-public compute access information
- sensitive dataset, model, or infrastructure details that are not already public

If you already posted sensitive material, edit it out immediately and email hello@limeslabs.eu with `[security]` in the subject.

## What is in scope

- exposed secrets or credentials
- unsafe GitHub Actions or release workflows
- dependency or supply-chain issues in project code
- data leakage in examples, logs, templates, or documentation
- vulnerabilities in public tools maintained by Limes Labs
- security risks in benchmark or model-running instructions

## What is out of scope

- speculative reports without a concrete affected asset
- social engineering, phishing, or physical attacks
- denial-of-service testing without prior written permission
- scanning or testing systems not owned or explicitly operated by Limes Labs

## Response expectations

This is an early project without a formal security team. Maintainers will make a good-faith effort to acknowledge reports within 7 days, assess severity, and coordinate a fix or public note when appropriate.

Public disclosure should wait until maintainers have had a reasonable opportunity to assess and remediate the issue.
