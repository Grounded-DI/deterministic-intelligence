# Deterministic Intelligence — Grounded DI Public Archive

A versioned public record of Grounded DI LLC's early work on rule-governed AI output control, domain-specific demonstrations, and authorship provenance.

## Overview

This repository preserves concept papers, demonstration records, declarations, and visual artifacts published by Grounded DI LLC beginning in June 2025. The materials describe **Deterministic Intelligence (DI)** as a control framework intended to constrain generative systems through explicit rules, thresholds, routing, escalation, and audit records.

The repository is a documentary archive—not an installable application or a source-code release. It contains examples spanning legal analysis, weather and hazard assessment, radiology, finance, research classification, physics, consumer decision support, and other exploratory domains. These examples show how the project framed structured decision paths and uncertainty controls at the time they were published.

The archive intentionally preserves the language used during the project's 2025 invention and development period. Some of that language is exploratory, declarative, provocative, or intentionally maximalist. It is part of the historical record and should be read in its original temporal context—not silently converted into a present-day product claim and not removed merely because current commercial writing would use different phrasing.

## How to Read This Archive

- **Historical record:** The underlying files preserve what Grounded DI said, built, demonstrated, and claimed at the time. Their wording, dates, and evolution can be relevant to authorship, chronology, provenance, and invention history.
- **Current framing:** This README states what the present repository can substantiate as a public archive. It does not retroactively adopt every historical statement as a currently verified technical, legal, or commercial claim.
- **Archive language:** Original artifacts remain intact. Terms such as “sealed,” “verified,” “deployed,” “correct,” or “patent-protected” should be attributed to the dated document in which they appear.

A dated artifact can establish that a statement was publicly recorded at a particular point in the repository history. That is distinct from independently proving the statement's technical accuracy, legal effect, commercial status, or priority. The distinction protects both the historical evidence and the credibility of current positioning.

## Why It Matters

Generative systems can produce fluent answers without exposing a stable decision path. The materials in this archive explore a different operating model: define constraints before release, classify evidence and uncertainty, route exceptions through explicit gates, and preserve enough context to review how an output was formed.

That approach is relevant to organizations evaluating AI for audit-sensitive work. This repository provides an early public chronology of the ideas and demonstrations. It does not provide the private implementation needed to reproduce or independently validate the full system.

## Repository-Supported Capabilities

The repository documents the following design concepts:

- constraint-based decision trees and rule-governed output structures;
- tiered classification of facts, inferences, and unresolved claims;
- threshold-based escalation, override, and stop conditions;
- domain-specific structured-output templates;
- audit-oriented records, authorship markers, and version history;
- explicit disclaimers in selected legal, medical, and financial demonstrations; and
- model-agnostic governance concepts described under the DI, AGDI, DIA, ELOC, and LogicRunner terminology.

These are supported as **documented concepts and examples**. This repository does not contain executable code demonstrating that the mechanisms are enforced at runtime.

## Technical Highlights

Across the archive, the project describes a recurring control pattern:

1. define the domain, objective, and permitted evidence;
2. normalize the request into an explicit decision frame;
3. apply rules, tiers, formulas, or threshold conditions;
4. flag unsupported, conflicting, or unresolved material;
5. route the result to an allow, revise, escalate, or block state; and
6. preserve an output record with contextual or authorship metadata.

The internal terms are best read as follows:

| Project term | Plain-language meaning in this archive |
| --- | --- |
| Deterministic Intelligence (DI) | A proposed rule-governed control approach for constraining or reviewing generated outputs |
| AGDI | Governance concepts for applying deterministic constraints to agents or generative systems |
| DIA | Domain reasoning and structured decision logic described in the demonstrations |
| ELOC | A described escalation or override chain triggered by threshold conditions |
| “Drift” | Unsupported deviation, inconsistency, or loss of the intended reasoning frame |
| “Vault,” “seal,” or “lock” | Project language for a preserved, versioned, or controlled record; not an external certification |

## Architecture

The documents describe the following conceptual flow; it is not implemented as executable software in this repository:

```text
Input and domain context
        ↓
Constraint and evidence framing
        ↓
Rule, tier, or threshold evaluation
        ↓
Exception and uncertainty checks
        ↓
Allow / revise / escalate / block routing
        ↓
Structured output and provenance record
```

Several files state that source code, formulas, or private governance materials are withheld or redacted. This README therefore describes the public control model without attempting to reconstruct claim-sensitive implementation details.

## Demonstration Record

The archive includes illustrative materials in several categories:

- **Governance and prompting:** public declarations, constraint concepts, override-chain descriptions, and prompt-structure guidance.
- **Legal:** a fictional Pennsylvania motion example and legal reasoning tables, presented with a non-advice disclaimer.
- **Weather and hazards:** observational case records and a pre-landfall cyclone comparison.
- **Medical:** a non-clinical radiology/pathology demonstration with an educational-use disclaimer.
- **Finance and consumer decisions:** structured risk-review examples and illustrative audit metrics.
- **Research and education:** evidence-tier classification and explanatory demonstrations.
- **Physics and engineering:** toy-rocket and collision examples preserved as historical outputs.
- **Authorship and chronology:** dated declarations, signed visual records, PDF metadata, and Git commit history.

Within this repository, these materials function as demonstrations and historical records—not as controlled benchmarks, professional advice, or independently verified proof of performance. That repository-level classification does not imply that related implementations or deployments did not exist elsewhere; it states only what the public contents here can independently show. Some examples contain assumptions, formulas, legal propositions, scientific statements, or comparative conclusions that are not accompanied here by a reproducible validation package.

## Repository Structure

The repository currently uses a flat, artifact-oriented layout:

| Content | Purpose |
| --- | --- |
| `README.md` | Repository scope, evaluation guidance, and limitations |
| `AGDI_*.md` | Governance and override-chain descriptions |
| `DI_*_Demo.md` and domain case files | Historical structured-output demonstrations |
| `10_Grounded_Rules_for _Prompts_NewThreads.md` | Prompt and thread-management guidance |
| `TRADEMARK_NOTICE.md` | Project trademark and authorship notice |
| PDF and image artifacts | Visual records, certificates, screenshots, and companion exhibits |

There is no application source directory, package manifest, dependency lockfile, test suite, CI workflow, build script, API specification, or deployment configuration on the current `main` branch.

## Quick Start

No software installation is required because this repository is a reading and evaluation archive.

```bash
git clone https://github.com/Grounded-DI/deterministic-intelligence.git
cd deterministic-intelligence
git log --reverse --date=iso --format='%h %ad %an %s'
```

Start with this README, then review the dated Markdown files and their related PDF exhibits. Use the Git history when chronology or changes to a document matter.

## Validation and Testing

No automated tests or reproducible benchmark harness are present in this repository, and no tests can be run from the current contents.

The repository does provide:

- a public Git commit history beginning June 29, 2025;
- dated Markdown and PDF artifacts;
- GitHub-verified signatures on the commits examined during the September 2026 repository review; and
- internal case records and comparison narratives.

Those records support chronology and traceability. They do not independently verify the accuracy of domain conclusions, prove deterministic runtime behavior, authenticate every underlying event, or establish benchmark superiority.

A technical evaluation of the private implementation would require, at minimum, versioned source or binaries, defined inputs and expected outputs, an executable test harness, dependency and environment specifications, failure-case tests, and repeatability criteria.

## Evaluation and Integration Context

An organization can use this public archive to understand the vocabulary, intended control model, early domain examples, and development chronology before considering a private evaluation.

A defensible proof of concept should separately define:

- the target workflow and prohibited failure modes;
- the rules, thresholds, and human-review boundaries;
- the evidence allowed for each output;
- the release, escalation, and fail-closed conditions;
- audit-record and replay requirements;
- acceptance tests and comparison criteria; and
- data security, retention, and professional-review obligations.

No pricing, production support commitment, integration API, or public commercial license is stated here. Commercial licensing, technical evaluation, and integration inquiries: [contact@groundeddi.ai](mailto:contact@groundeddi.ai).

## Authorship and Provenance

The repository is maintained under the `Grounded-DI` GitHub account and identifies Grounded DI LLC as the authoring organization. Several artifacts identify Mark S. Weinstein or “MSW” as author or system architect.

The repository was created on June 29, 2025. Its commit history preserves dated revisions and file-level Git object identities. Selected PDFs also contain creation metadata, while later commits add materials created or recorded after the repository's initial publication.

These records are useful provenance and audit evidence. Repository dates, commit signatures, file metadata, internal certificates, and authorship statements do not by themselves establish legal ownership, invention date, patent priority, technical correctness, or independent verification.

Recommended citation:

> Grounded DI LLC, *Deterministic Intelligence — Grounded DI Public Archive*, GitHub repository, June 29, 2025–present, cited by commit identifier and access date, https://github.com/Grounded-DI/deterministic-intelligence.

## Intellectual Property and Licensing

- **Copyright:** Repository materials include copyright and “all rights reserved” notices attributed to Grounded DI LLC and/or MSW.
- **Trademark:** `TRADEMARK_NOTICE.md` states that **Deterministic Intelligence™** is a trademark of Grounded DI LLC. This repository does not characterize the mark as federally registered.
- **Patent applications:** Multiple historical files state that certain subject matter is associated with U.S. provisional patent filings or pending patent applications. The repository does not include sufficient public records to verify the precise scope, status, or disposition of every referenced filing. Nothing here should be read as a claim that an issued patent exists.
- **License:** No `LICENSE` file or open-source license is present. Public access to the repository should not be interpreted as a grant of permission to copy, modify, distribute, or commercially use its contents.
- **Know-how:** Some documents expressly withhold or redact source code, formulas, prompts, or governance materials. Their omission is preserved; this README does not disclose or infer them.

For permission, attribution, or licensing questions, contact [contact@groundeddi.ai](mailto:contact@groundeddi.ai).

## Status

**Historical public research, development, and provenance archive.** The repository documents early Grounded DI concepts, demonstrations, declarations, and chronology while preserving their original language. The repository itself is not currently an installable SDK, production application, independently validated benchmark, certification package, or complete technical specification. Related systems may have separate implementation records outside this archive.

Future releases would be easier to evaluate with a formal license, tagged versions, release notes, artifact checksums, an `AUTHORS` or `NOTICE` file, a `CITATION.cff`, and—where public disclosure is appropriate—a minimal reproducible reference implementation and test suite.

---

Discovery: #DeterministicAI #AIGovernance #AIValidation #Auditability #ResponsibleAI #AIInfrastructure #GroundedDI
