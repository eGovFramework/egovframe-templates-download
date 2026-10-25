# egovframe-templates-download: project context

## Role and maintenance boundary

A repository described as versioned legacy project-template archives for the VSCode Initializr extension. Preserve published template naming/version semantics and the downstream Initializr consumption contract when artifacts are present.
This card reflects source inspection at adoption; it does not certify runtime behavior.

## Public entry points and evidence

- `README.md`: describes versioned eGovFrame project template archives for VSCode Initializr legacy support.
- The tracked work tree at adoption contains only `README.md`; no archive, manifest, build script, test suite, or GitHub Actions workflow is present. The description is intended purpose, not evidence of existing downloadable artifacts.

## Build and verification entry points

There is no checked-in application build or test command to run. For a future artifact
change, first identify the actual archive and downstream consumer contract, inspect its
contents and version naming, and perform an isolated consumer extraction/scaffold check.
Do not invent a Maven, npm, or Flutter build for this repository. Adoption validation covers
only the Spec Kit commands and disposable workflow scaffold.

## Environment and evidence limits

No runnable application or template archive was available in the inspected tracked tree.
Public fork issue #1 asks to confirm repository substance; that remains a follow-up and is
not resolved by adding workflow documentation.
No application build, test suite, formatter, device test, or external service was run for this
workflow-only adoption. A Spec Kit CLI/status and isolated scaffold smoke validate the tooling
only. No CodeGraph index was present in the adoption workspace; targeted file listing and
exact text inspection supplied the evidence, without installing an indexer.

## Upstream and submission baseline

Upstream: [eGovFramework/egovframe-templates-download](https://github.com/eGovFramework/egovframe-templates-download). Fetch the actual upstream default branch
and record its exact SHA before preparing `upstream-submit`; do not infer the baseline from
fork work. Preserve an existing submission branch or open PR. Adoption changes are pushed
only to fork `work`; an absent `upstream-submit` is created from the fetched upstream SHA
without adoption commits, as a separate submission baseline.
The [constitution](constitution.md) is the policy source for domain cards, verification, and
work-only artifact isolation. Native OMP commands are in `.omp/commands/`; the bundled bug
workflow provides assess, fix, and test stages. No application fix or PR is part of
this adoption.
