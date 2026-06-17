# Limes Labs GitHub Roadmap

This roadmap defines the first operating layer for the public GitHub organization. It is not a capability claim. It is a plan for making the work legible, reviewable, and useful to contributors.

## First 30 days

### Organization and onboarding

- Publish shared contributing, conduct, security, roadmap, and issue-template files in `.github`.
- Add a "choose a repository" path for researchers, engineers, legal/policy contributors, institutions, and funders.
- Create the first cross-repo issue backlog with concrete labels and review criteria.
- Add repo topics and common labels so work can be filtered by role and area.

### Constitution

- Turn public values into reviewable amendment issues.
- Add explicit review criteria for constitutional claims: source, principle, implementation implication, and known conflict.
- Identify first evaluation questions that connect the constitution to EuroBench tasks.

### Benchmarks and evaluation

- Define a small EuroBench task schema before expanding the suite.
- Add at least one inspectable task for Italian institutional language.
- Prepare a result log format that can capture failures and limitations, not only scores.

### Compute and infrastructure

- Convert EuroHPC, AI Factories, IT4LIA, and university access questions into sourced notes.
- Separate confirmed access paths from unknowns.
- Add a checklist for compute application readiness: entity, eligibility, project summary, data, security, budget, and reporting.

### Open weight tracking and model cards

- Define a minimal model metadata schema: model name, weights, license, languages, evals, deployment limits, sources.
- Add a model card section for European language coverage and institutional use constraints.
- Cross-link tracker entries to EuroBench results once reproducible results exist.

### Training experiments

- Keep `limes-nanogpt` focused on small, reproducible runs.
- Add GPU-hour estimates and configuration notes before requesting larger compute.
- Publish commands, configs, and failure notes for any run used in public claims.

## First 90 days

- Publish a first public benchmark report with methodology, limitations, and raw result references.
- Document at least one complete compute access path from public requirements to application-ready checklist.
- Maintain an open-weight tracker with a small number of well-sourced entries rather than a broad unverified catalog.
- Produce one example model card for a small reproducible experiment or external open weight model.
- Align `limes-nanogpt` outputs with EuroBench evaluation scripts.
- Create a governance path for constitution amendments and review cycles.
- Identify institutional collaborators or reviewers willing to validate public notes.

## Not yet

The following are explicitly out of scope until the public work supports them:

- claiming frontier or production-grade model capability
- claiming secured European compute access before it is documented
- publishing rankings without reproducible methodology
- hosting sensitive datasets or private institutional material
- releasing large model weights without clear license, safety, and documentation review
- treating policy notes as legal advice
- expanding to many repos before the current repos have clear owners and review paths

## How roadmap items become work

Each roadmap item should become one or more GitHub issues with:

- a concrete deliverable
- the relevant repository
- sources or starting references
- labels for role and area
- review expectations
- a clear definition of done
