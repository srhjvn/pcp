---
title: Service Intake Workflow
document_type: workflow
phase: Phase 2 - Service Enablement
status: draft
owner: Sarah Lynn LLC
source_of_truth: true
related_files:
  - ServiceFramework.md
  - ServiceAssetMap.md
  - ServiceReadinessChecklist.md
  - README.md
  - DecisionLog.md
  - PreferencesAndConstraints.md
  - CurrentProjects.md
purpose: >
  Defines the intake, classification, fit check, scoping, and routing flow
  for service-related requests within the Personal Context Portfolio system.
audience:
  - internal
update_frequency: as-needed
tags:
  - pcp
  - workflow
  - intake
  - phase-2
template_applied: true
template_name: standard-md-metadata-v1
---

# Service Intake Workflow

## Purpose

This file defines the standard intake path for service-related requests within the Personal Context Portfolio.

Its purpose is to make request handling more consistent by establishing:

- a repeatable intake sequence
- a standard way to classify requests
- a fit-check process before work is accepted
- a clear path for scoping and routing
- a simple start condition and end condition for the workflow

This file is intended to support lean service operations and should remain living documentation.

---

## Workflow Objective

The objective of this workflow is to move a request from initial appearance to one of four outcomes:

- ready to scope
- ready to draft
- needs supporting asset first
- not a fit

This workflow is designed to reduce ambiguity, protect scope, improve consistency, and surface missing service-enablement assets early.

---

## Workflow Design Principles

The intake workflow should follow these rules:

- keep intake lightweight
- classify before committing
- check fit before drafting
- reuse existing source material before creating new material
- identify missing assets early
- avoid accepting work that does not align with current service structure
- document decisions when routing materially changes

---

## Start and End Conditions

### Start Condition
A request, lead, idea, outreach, referral, or internal service need appears that may align with an active or emerging service offer.

### End Condition
The request has been classified, fit-checked, scoped to the appropriate next step, and routed into one of the approved outcomes.

---

## Workflow Overview

The intake workflow follows six stages:

1. capture request
2. classify request
3. assess fit
4. identify support status
5. define next-step scope
6. route outcome

---

## Workflow Stages

## Stage 1: Capture Request

### Objective
Record the request in a minimal but usable form before interpretation begins.

### Intake Capture Fields
Capture the following:

- request source
- requester name or label
- date received
- stated need
- stated urgency
- desired outcome
- available materials or context
- open questions or ambiguity notes

### Minimum Capture Standard
At minimum, the request record should answer:

- who is asking
- what they appear to need
- what problem they are trying to solve
- what kind of output they seem to expect
- whether timing matters

### Notes
Do not fully scope the work at this stage. The goal is only to preserve enough information for classification and fit review.

---

## Stage 2: Classify Request

### Objective
Match the request to the most likely service structure before deciding whether to proceed.

### Classification Fields
Classify the request using the following:

- likely service category
- likely service offer
- likely audience type
- likely problem pattern
- likely output type

### Service Category Options
- Strategic Clarity
- Documentation and Translation Support
- Personal Context Portfolio Enablement

### Common Problem Pattern Options
- scattered information
- unclear offer or positioning
- process exists but is undocumented
- language is too broad, abstract, or technical
- system exists but is hard to maintain
- output is needed but structure is missing

### Classification Notes
If a request appears to span multiple service offers, assign the primary offer first and note secondary alignment separately.

---

## Stage 3: Assess Fit

### Objective
Determine whether the request is a strong, partial, or poor fit for the current service structure.

### Fit Review Questions
Review the request against these questions:

- Does this align with an active or pilot-ready service offer?
- Is the problem understandable enough to describe clearly?
- Is the likely output something already supported by the service structure?
- Do current source files provide enough grounding to support the work?
- Is the request consistent with documented preferences and constraints?
- Is the request a reasonable match for the current operating direction?

### Fit Outcomes
Use one of the following fit markers:

- strong fit
- conditional fit
- weak fit
- non-fit

### Fit Interpretation

#### Strong Fit
The request clearly aligns with an active or pilot-ready offer and can be supported with existing source materials.

#### Conditional Fit
The request generally aligns, but some ambiguity, asset gaps, or scoping questions remain.

#### Weak Fit
The request has partial overlap with the service system, but the match is loose enough that proceeding may create confusion, inconsistency, or avoidable custom work.

#### Non-Fit
The request does not meaningfully align with the defined service structure or current priorities.

---

## Stage 4: Identify Support Status

### Objective
Determine whether the service is operationally supported enough to proceed.

### Support Status Review
Check the following:

- Are the relevant source files available?
- Is there a usable template already in place?
- Is there a comparable example or prior pattern?
- Is a readiness level already defined for the service offer?
- Would proceeding require creating missing infrastructure first?

### Support Status Markers
Use one of the following:

- supported
- partially supported
- unsupported

### Interpretation

#### Supported
The relevant files, patterns, and working structures are in place.

#### Partially Supported
Enough exists to proceed carefully, but one or more templates, examples, or assets are missing.

#### Unsupported
The request depends on assets, templates, or structures that do not yet exist.

---

## Stage 5: Define Next-Step Scope

### Objective
Set the immediate next step without overcommitting the full work too early.

### Define the Following
For requests that pass fit review, define:

- primary output
- likely service offer
- immediate next action
- required inputs
- likely dependencies
- known boundaries
- out-of-scope items, if visible
- whether an asset must be built first

### Immediate Next Action Options
- prepare scoped response
- draft initial document
- gather missing inputs
- create supporting template first
- route to backlog / future development
- decline / park

### Scope Notes
This stage is about defining the next operational move, not finalizing every detail of delivery.

---

## Stage 6: Route Outcome

### Objective
Move the request into a clear outcome state.

### Approved Outcome States

#### Ready to Scope
The request is a fit and can move into a more formal scoped-response step.

#### Ready to Draft
The request is clear enough, well-supported enough, and bounded enough to begin drafting.

#### Needs Supporting Asset First
The request is directionally valid, but a template, checklist, workflow, or other enablement asset should be created before work proceeds.

#### Not a Fit
The request should not move forward within the current service structure.

### Routing Record
The routing note should include:

- selected outcome state
- primary service offer
- fit marker
- support status
- immediate next action
- any missing asset identified
- any follow-up needed

---

## Intake Decision Logic

Use this simplified routing logic:

### Route to **Ready to Scope** when:
- the request is a strong or conditional fit
- the likely output is clear
- some support exists
- additional scoping would improve confidence

### Route to **Ready to Draft** when:
- the request is a strong fit
- the output is already clear
- source files and working patterns are sufficient
- missing assets do not block execution

### Route to **Needs Supporting Asset First** when:
- the request is a fit
- but execution depends on a missing template, checklist, or workflow component
- and creating that asset would improve repeatability or quality

### Route to **Not a Fit** when:
- the request is weak fit or non-fit
- the output does not align with an active offer
- or the request would force unnecessary custom structure outside the current system

---

## Intake Record Template

Use the following structure to log an intake review.

### Intake Record
- **Request Source:**  
- **Requester:**  
- **Date Received:**  
- **Stated Need:**  
- **Desired Outcome:**  
- **Urgency:**  
- **Available Inputs:**  
- **Likely Service Category:**  
- **Likely Service Offer:**  
- **Likely Problem Pattern:**  
- **Likely Output Type:**  
- **Fit Marker:**  
- **Support Status:**  
- **Missing Assets Identified:**  
- **Immediate Next Action:**  
- **Routing Outcome:**  
- **Notes:**  

---

## Example Intake Patterns

### Pattern 1: Clear Positioning Request
**Example:** A consultant needs clearer language for what they do and who they help.

**Likely Classification:**  
- Strategic Clarity
- Positioning and Offer Clarity

**Likely Fit:**  
strong fit

**Likely Support Status:**  
partially supported

**Likely Route:**  
ready to scope or ready to draft

---

### Pattern 2: Workflow Clarification Request
**Example:** A founder has a service process that works informally but is not documented.

**Likely Classification:**  
- Strategic Clarity
- Operational Clarity and Workflow Drafting

**Likely Fit:**  
strong fit

**Likely Support Status:**  
partially supported

**Likely Route:**  
needs supporting asset first or ready to scope

---

### Pattern 3: Raw Notes to Structured Document
**Example:** A requester has scattered notes and wants them turned into clean internal documentation.

**Likely Classification:**  
- Documentation and Translation Support
- Structured Documentation Support

**Likely Fit:**  
strong fit

**Likely Support Status:**  
supported or partially supported

**Likely Route:**  
ready to draft

---

### Pattern 4: Unclear or Overly Broad Request
**Example:** A request asks for “help with everything” without a defined problem or output.

**Likely Classification:**  
unclear

**Likely Fit:**  
conditional fit or weak fit

**Likely Support Status:**  
partially supported or unsupported

**Likely Route:**  
ready to scope, backlog, or not a fit depending on whether the problem can be bounded

---

## Related Assets and Dependencies

This workflow depends on:

- `ServiceFramework.md`
- `ServiceAssetMap.md`
- `ServiceReadinessChecklist.md`
- `PreferencesAndConstraints.md`
- `DecisionLog.md`

It should also remain aligned with active examples and priorities reflected in:

- `CurrentProjects.md`
- `GoalsAndPriorities.md`
- `README.md`

---

## Missing Workflow Support Assets

The following assets would strengthen this intake workflow:

- intake question set
- scoping template
- fit / non-fit routing guide
- service readiness checklist
- service summary template

These should be tracked in `ServiceAssetMap.md`.

---

## Maintenance Guidance

Update this file when:

- service categories change
- service offers change
- fit rules materially change
- routing outcomes change
- intake fields are refined
- new workflow support assets are created

Record major changes in `DecisionLog.md`.

---

## Definition of Done

This workflow is functioning as intended when:

- requests can be captured consistently
- requests can be classified quickly
- fit can be assessed using standard logic
- missing assets can be identified before drafting begins
- requests can be routed into a small set of clear outcomes
- intake decisions are repeatable enough to support service operations
