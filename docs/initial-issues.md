# Proposed Initial GitHub Issues

These are draft issues for the first 30-day operating layer. They are not created automatically. Maintainers can copy them into the target repositories, adjust labels, and assign owners.

## 1. Define constitution amendment review criteria

- Repo: `Limes-Labs/limes-constitution`
- Labels: `constitution`, `governance`, `good first issue`, `needs source`

### Body

Create a short review checklist for proposed changes to `CONSTITUTION.md`.

The checklist should cover:

- the principle being changed or added
- source or rationale
- expected implication for assistants or evaluation
- possible conflict with other principles
- whether the change is normative, operational, or legal/policy-related

Definition of done:

- [ ] Checklist is added to the repository.
- [ ] README links to it.
- [ ] The checklist avoids legal advice and does not overclaim current capability.

## 2. Map constitution principles to first EuroBench evaluation questions

- Repo: `Limes-Labs/limes-constitution`
- Labels: `constitution`, `benchmark`, `research`

### Body

Create a table mapping 5-8 constitution principles to concrete evaluation questions that EuroBench could test later.

Example fields:

- principle
- behavior to inspect
- possible benchmark prompt or task type
- expected failure mode
- related EuroBench issue or file

Definition of done:

- [ ] Table is added as a markdown document.
- [ ] Each row describes a testable behavior.
- [ ] The document states that these are proposed evaluation questions, not proven model behavior.

## 3. Write a EuroBench task schema for small European language tasks

- Repo: `Limes-Labs/eurobench`
- Labels: `benchmark`, `evaluation`, `good first issue`

### Body

Define a minimal task schema that contributors can use before adding more tasks.

Suggested fields:

- task name
- language
- domain
- input format
- expected output format
- scoring method
- source and license
- known limitations
- example item

Definition of done:

- [ ] Schema is documented in the repo.
- [ ] One existing or proposed task is converted to the schema.
- [ ] The schema includes source and license fields.

## 4. Add an Italian public administration task example

- Repo: `Limes-Labs/eurobench`
- Labels: `benchmark`, `italian`, `evaluation`, `needs source`

### Body

Add one inspectable benchmark task for Italian public administration language.

The task should be small, public, and reviewable. It can target summarization, information extraction, classification, or question answering, but it must include source and license notes.

Definition of done:

- [ ] Public source is linked.
- [ ] Task format follows the EuroBench task schema.
- [ ] Example input and expected output are included.
- [ ] Known limitations are documented.

## 5. Create a compute access readiness checklist

- Repo: `Limes-Labs/compute-access-notes`
- Labels: `compute`, `documentation`, `good first issue`

### Body

Create a checklist for preparing a European compute access application or institutional conversation.

Suggested sections:

- legal entity and eligibility
- project summary
- compute requirements
- data and security
- expected outputs
- reporting obligations
- budget or co-funding questions
- contact and timeline notes

Definition of done:

- [ ] Checklist is added as a markdown file.
- [ ] README links to it.
- [ ] The checklist distinguishes confirmed requirements from preparation questions.

## 6. Document EuroHPC access paths with confirmed sources and unknowns

- Repo: `Limes-Labs/compute-access-notes`
- Labels: `compute`, `eurohpc`, `needs source`, `research`

### Body

Create a sourced note summarizing EuroHPC access paths relevant to startups, SMEs, researchers, and open source AI contributors.

The note should separate:

- confirmed public requirements
- possible routes that need validation
- unknowns for Limes Labs
- next contacts or public pages to monitor

Definition of done:

- [ ] Official sources are linked.
- [ ] Unknowns are listed explicitly.
- [ ] No private contacts or confidential correspondence are included.

## 7. Define the open-weight tracker metadata schema

- Repo: `Limes-Labs/open-weight-tracker`
- Labels: `open-weights`, `metadata`, `good first issue`

### Body

Define the first metadata schema for tracking open weight models relevant to European languages and use cases.

Suggested fields:

- model name and version
- release organization
- weights availability
- license
- architecture or family
- supported languages claimed by source
- European language evidence
- evaluation links
- deployment constraints
- source URLs

Definition of done:

- [ ] Schema is documented.
- [ ] At least one example entry is included.
- [ ] The schema distinguishes claims from independently reproduced results.

## 8. Add European language coverage section to the model card template

- Repo: `Limes-Labs/model-card-template`
- Labels: `model-card`, `documentation`, `policy`

### Body

Add a section to the model card template for European language coverage and known limitations.

The section should ask model publishers to document:

- languages tested
- scripts and dialect considerations
- benchmark sources
- observed failure modes
- unsupported languages
- whether results are self-reported or independently reproduced

Definition of done:

- [ ] Template includes the new section.
- [ ] Guidance text avoids implying coverage where none is measured.
- [ ] Example wording is included for unknown or untested languages.

## 9. Estimate laptop and GPU-hour requirements for limes-nanogpt configs

- Repo: `Limes-Labs/limes-nanogpt`
- Labels: `training`, `reproducibility`, `compute`, `good first issue`

### Body

Document expected runtime, memory, and rough GPU-hour requirements for the existing `train_european_char.py` flow and any planned next config.

Include:

- CPU and Apple Silicon notes where known
- small GPU assumptions if available
- commands used
- hardware used for measurement
- limitations and variance

Definition of done:

- [ ] README or a docs file lists commands and observed runtime.
- [ ] Hardware assumptions are explicit.
- [ ] Notes do not imply large-scale capability.

## 10. Add a reproducible evaluation handoff from limes-nanogpt to EuroBench

- Repo: `Limes-Labs/limes-nanogpt`
- Labels: `evaluation`, `benchmark`, `training`

### Body

Define how a small `limes-nanogpt` checkpoint or generated output should be handed off to EuroBench for evaluation.

The first version can be documentation only. It should specify:

- output artifact names
- generation command
- config reference
- expected EuroBench input format
- result log location
- limitations for tiny or char-level models

Definition of done:

- [ ] Handoff steps are documented.
- [ ] At least one example command is included.
- [ ] The document states limitations for early small-model runs.
