---
title: Service Asset Map
document_type: asset_map
phase: Phase 2 - Service Enablement
status: draft
owner: Sarah Lynn LLC
source_of_truth: true
related_files:
  - ServiceFramework.md
  - ServiceReadinessChecklist.md
  - ServiceIntakeWorkflow.md
  - README.md
  - Identity.md
  - RolesandResponsibilities.md
  - GoalsAndPriorities.md
  - CurrentProjects.md
  - ToolsAndSystems.md
  - CommunicationStyle.md
  - PreferencesAndConstraints.md
  - DomainKnowledge.md
  - DecisionLog.md
purpose: >
  Maps service offers to outputs, source files, templates, dependencies,
  and missing assets needed to support service delivery readiness.
audience:
  - internal
update_frequency: as-needed
tags:
  - pcp
  - services
  - asset-map
  - phase-2
template_applied: true
template_name: standard-md-metadata-v1
---

# Service Asset Map

## Purpose

This file maps each defined service offer to the materials required to support delivery.

It is intended to make the service layer operational by identifying:

- what each service produces
- which source files inform delivery
- which templates support consistency
- which assets already exist
- which assets are still missing
- what is needed for a service to move from draft to pilot or ready status

This file is living documentation and should be updated as the service system matures.

---

## How to Use This File

Use this file to:

- assess whether a service offer is operationally supported
- identify reusable source material before creating new documentation
- spot template and asset gaps
- support service readiness reviews
- guide build order for missing enablement materials

This file should stay aligned with:

- `ServiceFramework.md`
- `ServiceIntakeWorkflow.md`
- `ServiceReadinessChecklist.md`
- `README.md`
- core PCP source files

---

## Asset Mapping Standard

Each service offer should be reviewed using the following structure:

- **Service Offer**
- **Typical Outputs**
- **Primary Source Files**
- **Supporting Source Files**
- **Templates Available**
- **Templates Needed**
- **Example Assets Available**
- **Missing Assets**
- **Current Readiness**
- **Notes**

---

## Service Asset Map Table

| Service Offer | Typical Outputs | Primary Source Files | Supporting Source Files | Templates Available | Templates Needed | Example Assets Available | Missing Assets | Current Readiness | Notes |
|---|---|---|---|---|---|---|---|---|---|
| Positioning and Offer Clarity | service summary, positioning sheet, audience/problem statement, overview copy | `Identity.md`, `GoalsAndPriorities.md`, `CommunicationStyle.md` | `PreferencesAndConstraints.md`, `RolesandResponsibilities.md`, `DecisionLog.md` | none standardized yet | service summary template, positioning template, offer language template | distributed examples may exist across prior drafts | standardized template set, example library, concise client-facing one-pager | Partially Ready | Strong source material exists, but packaging assets need formalization |
| Operational Clarity and Workflow Drafting | workflow draft, process map, service path, maintenance notes | `CurrentProjects.md`, `ToolsAndSystems.md`, `DecisionLog.md` | `RolesandResponsibilities.md`, `PreferencesAndConstraints.md` | partial workflow pattern exists conceptually | workflow template, process map template, maintenance checklist | existing workflow discussions and repo guidance drafts | standardized workflow template, completion checklist, routing/status markers | Partially Ready | Good fit for internal system support once standardized |
| Structured Documentation Support | structured summaries, internal docs, scoped write-ups, organized markdown files | `DomainKnowledge.md`, `ToolsAndSystems.md`, `RolesandResponsibilities.md` | `CommunicationStyle.md`, `CurrentProjects.md` | informal drafting pattern exists | document request template, QA checklist, document output template | likely strongest existing capability based on current work style | intake questions, QA pass checklist, reusable output template | Ready to Pilot | Lowest friction service to operationalize quickly |
| Problem-to-Solution Language Development | problem/solution statements, service language blocks, audience-facing summaries | `Identity.md`, `CommunicationStyle.md`, `DomainKnowledge.md` | `GoalsAndPriorities.md`, `PreferencesAndConstraints.md` | none standardized yet | messaging template, before/after example set, language block template | examples likely exist in prior messaging work | reusable template, example bank, fit/use-case notes | Partially Ready | Strong capability, but currently too dependent on custom drafting |
| PCP Setup and Refinement | PCP structure, README updates, file mapping guidance, maintenance notes | `README.md`, `DecisionLog.md`, all core PCP files | `CurrentProjects.md`, `GoalsAndPriorities.md` | partial repo structure and file list already exist | onboarding sequence, maintenance checklist, setup guide template | strongest system-level example is the current PCP itself | standardized onboarding doc, checklist, before/after setup example | Ready to Pilot | Especially useful as an internal or portfolio-backed service |

---

## Source File Contribution Guide

This section clarifies what each core file is most likely to contribute to service delivery.

### `Identity.md`
Best used for:
- positioning inputs
- role framing
- credibility language
- identity-level service alignment

### `RolesandResponsibilities.md`
Best used for:
- scope clarification
- responsibility framing
- delivery boundaries
- capability translation

### `GoalsAndPriorities.md`
Best used for:
- current direction
- near-term strategic emphasis
- active service priorities
- alignment checks

### `CurrentProjects.md`
Best used for:
- active examples
- current build work
- proof of ongoing relevance
- workflow grounding

### `ToolsAndSystems.md`
Best used for:
- methods and systems references
- operational environment context
- process/tool support
- implementation grounding

### `CommunicationStyle.md`
Best used for:
- tone consistency
- audience-facing language
- writing style alignment
- messaging refinement

### `PreferencesAndConstraints.md`
Best used for:
- rules and guardrails
- fit screening
- delivery boundaries
- “always / never” logic

### `DomainKnowledge.md`
Best used for:
- niche language
- domain expertise
- structured industry context
- documentation support

### `DecisionLog.md`
Best used for:
- rationale tracking
- status change context
- service evolution notes
- governance support

### `README.md`
Best used for:
- navigation
- system orientation
- use-path guidance
- service-layer entry point

---

## Template Status Overview

## Existing or Partial Patterns
The following patterns appear to exist in partial or informal form:

- modular markdown structure
- living documentation approach
- linked core source files
- workflow thinking with start/end conditions
- readiness-oriented documentation mindset

These are useful foundations, but they are not yet sufficient as standardized service templates.

## Priority Templates to Build

### Priority 1
These most directly support service activation:

- service summary template
- workflow template
- intake template
- service readiness checklist
- document request template

### Priority 2
These improve consistency and scale:

- positioning template
- messaging template
- scoping template
- maintenance checklist
- client-facing one-page overview template

### Priority 3
These improve proof and reuse:

- example output library
- before/after transformation examples
- onboarding sequence
- fit/non-fit routing guide

---

## Missing Asset Register

Use this section as the working list of missing assets to create.

| Asset | Asset Type | Supports Which Service(s) | Priority | Status | Notes |
|---|---|---|---|---|---|
| Standard service summary template | template | Positioning and Offer Clarity, Problem-to-Solution Language Development | P1 | not started | Needed to standardize service articulation |
| Workflow template | template | Operational Clarity and Workflow Drafting, PCP Setup and Refinement | P1 | not started | Should include start condition, end condition, source links, and status |
| Intake question set | workflow asset | all services | P1 | not started | Needed to classify and route requests consistently |
| Service readiness checklist | checklist | all services | P1 | not started | Should align to readiness markers in `ServiceFramework.md` |
| Document request template | template | Structured Documentation Support | P1 | not started | Likely fastest service-enablement gain |
| Positioning template | template | Positioning and Offer Clarity | P2 | not started | Helps convert scattered experience into market-ready language |
| Messaging template | template | Problem-to-Solution Language Development | P2 | not started | Should connect problem, current state, solution, output, result |
| Scoping template | template | all services | P2 | not started | Useful once intake is active |
| Maintenance checklist | checklist | Operational Clarity and Workflow Drafting, PCP Setup and Refinement | P2 | not started | Supports living-documentation upkeep |
| Client-facing one-page service overview | client asset | all externally presented services | P2 | not started | Useful only after internal structure is stable |
| Example output library | reference asset | all services | P3 | not started | Can be built gradually from real work |
| Before/after examples | reference asset | Problem-to-Solution Language Development, Structured Documentation Support | P3 | not started | Helpful for proof and clarity |
| PCP onboarding sequence | workflow asset | PCP Setup and Refinement | P3 | not started | Useful for reuse and repeatability |
| Fit / non-fit routing guide | reference asset | all services | P3 | not started | Helps protect scope and improve lead qualification |

---

## Readiness Interpretation

### Ready
The service has clear source support, usable templates, and enough structure to deliver consistently now.

### Ready to Pilot
The service can be delivered with current materials, but delivery still depends on judgment, adaptation, or informal methods.

### Partially Ready
The service is conceptually clear and source-supported, but lacks one or more templates, examples, or workflow assets needed for consistent execution.

### Not Ready
The service should not yet be treated as operational.

---

## Build Order Recommendation

To make the service system usable as quickly as possible, build missing assets in this sequence:

1. service summary template
2. workflow template
3. intake question set
4. service readiness checklist
5. document request template
6. messaging template
7. scoping template
8. maintenance checklist
9. one-page service overview
10. example output library

This order favors immediate operational enablement over polish.

---

## Maintenance Guidance

Update this file when:

- a new service offer is added or removed
- a template is created
- an asset status changes
- a source file becomes materially more relevant to a service
- a service readiness status changes
- an example asset library begins to form

Major updates should be reflected in `DecisionLog.md`.

---

## Phase 2 Use Standard

This file is working correctly when it allows someone reviewing the PCP to answer these questions quickly:

- What does each service produce?
- What source material supports it?
- What templates exist?
- What is missing?
- Which service is closest to usable now?
- What should be built next?
