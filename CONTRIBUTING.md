# Contributing to Limes Labs

Limes Labs is an early European open AI capability project. The current public stance is simple:

> We are not claiming capability yet. We are organizing capability.

This means contributions should turn open questions into sourced notes, reproducible code, reviewable evaluation tasks, and clear public documentation. Please keep the tone serious, specific, and non-hype.

## Fast path for new contributors

1. Choose the repository that matches your contribution.
2. Open an issue using the closest template, unless you are fixing a small typo or broken link.
3. Wait for basic alignment on scope when the change affects methodology, claims, policy, security, or public positioning.
4. Submit a focused pull request with sources, assumptions, and limitations.

If you are unsure where to start, open an issue in [Limes-Labs/.github](https://github.com/Limes-Labs/.github) using the bug/report template and mark it as a routing question.

## Roles we welcome

| Role | Useful contributions |
| --- | --- |
| Researchers | Benchmark design, literature review, evaluation methodology, failure analysis |
| ML engineers | Reproducible training runs, configs, checkpoints, evaluation harnesses, data preparation |
| Infrastructure engineers | Compute access notes, GPU-hour estimates, deployment constraints, reproducibility tooling |
| Legal and policy contributors | EU AI Act interpretation notes, licensing review, institutional procurement constraints |
| Technical writers | Model cards, README improvements, issue triage, source summaries |
| Institutional contributors | Contact paths, eligibility notes, program requirements, review of public claims |
| Funders and operators | Clear constraints, funding questions, compute access pathways, milestones |

## Choose the right repository

| Repository | Use it for | Do not use it for |
| --- | --- | --- |
| [limes-constitution](https://github.com/Limes-Labs/limes-constitution) | Values, public-interest behavior, rights-aware assistant expectations, amendment proposals | General political debate without a concrete text change |
| [eurobench](https://github.com/Limes-Labs/eurobench) | European language tasks, benchmark methodology, evaluation harness design, reproducible results | Unsupported claims that one model is broadly better |
| [compute-access-notes](https://github.com/Limes-Labs/compute-access-notes) | EuroHPC, AI Factories, IT4LIA, eligibility, application paths, public source notes | Private credentials, unpublished application material, or confidential contacts |
| [european-ai-infrastructure-map](https://github.com/Limes-Labs/european-ai-infrastructure-map) | Public map of labs, programs, infrastructure, funding paths, communities, startups | Promotional listings without evidence or relevance |
| [open-weight-tracker](https://github.com/Limes-Labs/open-weight-tracker) | Open weight model metadata, licenses, European language coverage, reproducible evaluation records | Closed model rankings or unverified benchmark claims |
| [model-card-template](https://github.com/Limes-Labs/model-card-template) | Model card sections, examples, safety and transparency notes, deployment documentation | Marketing pages for models |
| [limes-nanogpt](https://github.com/Limes-Labs/limes-nanogpt) | Small reproducible training experiments, configs, code, logs, integration with EuroBench | Claims about frontier capability |
| [.github](https://github.com/Limes-Labs/.github) | Organization profile, shared community files, templates, roadmap, onboarding | Repo-specific implementation details |

## Contribution paths

### Research and benchmark work

- State the question being tested.
- Describe the task, expected input/output, scoring method, and language coverage.
- Include sources for datasets, licenses, and known limitations.
- Prefer small, inspectable examples before broad benchmark suites.

### Compute access notes

- Cite public sources whenever possible.
- Separate facts from interpretation.
- Do not publish confidential contacts, credentials, application drafts, or private institutional correspondence.
- Mark unknowns clearly.

### Legal and policy notes

- This project does not provide legal advice.
- Cite primary sources when available, such as regulations, official guidance, procurement rules, or program pages.
- Explain the practical implication for open AI work in Europe.
- Flag jurisdiction-specific assumptions.

### Code contributions

- Keep changes small and reproducible.
- Include commands used to test or run the change.
- Avoid adding large dependencies unless the repository already uses them or the issue discusses the tradeoff.
- Do not add datasets, weights, credentials, or private documents unless the repo explicitly permits them.

### Documentation contributions

- Prefer clear statements with sources over broad claims.
- Include limitations and open questions.
- Link related repositories when work crosses boundaries.

## Review expectations

Maintainers should aim to review small pull requests quickly, but this is an early project and response time may vary.

Expect closer review for:

- capability claims
- benchmark methodology
- legal, safety, or policy interpretations
- security-sensitive changes
- files that shape public positioning
- changes that add dependencies, datasets, or generated artifacts

A good pull request includes:

- a short summary
- links to related issues
- sources or commands used
- known limitations
- screenshots or logs when relevant

## Public claims and evidence

Do not overstate the project. In particular:

- Do not claim that Limes Labs has frontier model capability.
- Do not imply secured compute access unless the relevant repo documents it.
- Do not publish model quality claims without methodology and reproducible evidence.
- Do not describe early experiments as production systems.

## Security and sensitive information

Do not publish credentials, secrets, private contacts, exploit details, non-public institutional information, or sensitive vulnerability reproduction steps in issues or pull requests.

For responsible disclosure, follow [SECURITY.md](SECURITY.md).

## Conduct

Participation is governed by [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md). The short version: be rigorous, direct, and respectful. Critique claims and methods, not people.
