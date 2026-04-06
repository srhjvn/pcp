---
status: Draft
last_updated: 2026-04-06
related_files:
  - [README.md](README.md)
  - [GoalsAndPriorities.md](GoalsAndPriorities.md)
  - [CurrentProjects.md](CurrentProjects.md)
  - [DecisionLog.md](DecisionLog.md)
  - [PreferencesAndConstraints.md](PreferencesAndConstraints.md)
review_date: 2026-07-06
---

# Operating Rhythm

This file owns the review cadence, update triggers, and stale-content maintenance rules for the Personal Context Portfolio.

## Purpose

This file defines the maintenance rhythm for the Personal Context Portfolio. Its purpose is to keep the repository current, useful, and trustworthy over time without creating unnecessary administrative overhead.

The operating rhythm is intended to support living documentation rather than static recordkeeping. Reviews should focus on clarity, accuracy, relevance, and boundary discipline across files.

---

## Weekly Review Rhythm

A lightweight weekly review should be used to keep active files aligned with current work and current priorities.

### Weekly review focus

During the weekly review, check:

- whether current priorities still reflect actual focus
- whether active projects still reflect current status and next steps
- whether any meaningful decisions should be added to the decision log
- whether any file now contains content that belongs somewhere else
- whether any file should be updated due to recent work, changes, or decisions

### Weekly review files

Weekly review should usually focus on:

- `GoalsAndPriorities.md`
- `CurrentProjects.md`
- `DecisionLog.md`

Other files should be reviewed weekly only if recent changes or active work make review necessary.

### Weekly review standard

The weekly review does not require full-file rewriting.  
It is a maintenance checkpoint intended to:

- confirm current relevance
- make small corrections
- capture meaningful change
- prevent drift between active files

---

## Monthly Review Rhythm

A broader monthly review should be used to check structural clarity, file boundaries, and maintenance needs across the portfolio.

### Monthly review focus

During the monthly review, check:

- whether file ownership boundaries are still clear
- whether duplicate or drifting content has appeared
- whether metadata remains accurate
- whether cross-references still reflect actual file relationships
- whether any inactive or reference-only files should be archived or marked superseded
- whether governance rules still fit the way the repository is being used

### Monthly review files

The monthly review should include a broader pass across the core file set:

- `README.md`
- `Identity.md`
- `RolesandResponsibilities.md`
- `GoalsAndPriorities.md`
- `CurrentProjects.md`
- `TeamAndRelationships.md`
- `ToolsAndSystems.md`
- `CommunicationStyle.md`
- `PreferencesAndConstraints.md`
- `DomainKnowledge.md`
- `DecisionLog.md`
- `ServiceOfferings.md`
- `ServicesSummary.md`

### Monthly review standard

The monthly review is the primary maintenance pass for the system as a whole. It should be used to:

- tighten boundaries
- remove duplication
- archive outdated material when needed
- confirm that the repository still functions as a usable operating system

---

## Update Triggers

Files should also be updated outside the weekly or monthly review rhythm when specific events occur.

### Update a file when:

- a meaningful decision has been made
- a priority has changed
- a project status has materially changed
- a new workflow, rule, or operating standard has been established
- a file is being actively used and current content is incomplete or inaccurate
- a cross-reference is broken or no longer reflects the actual source of truth
- a file has been replaced, split, merged, or retired

### Update trigger principle

Do not wait for a scheduled review if the file is actively supporting current work and has become inaccurate, incomplete, or misleading.

Scheduled reviews provide maintenance rhythm.  
Meaningful change should still trigger direct updates when needed.

---

## Stale-Content Review Rule

A file should be treated as potentially stale when any of the following is true:

- its `review_date` has passed
- its content no longer reflects current reality
- it is repeatedly bypassed in favor of another file
- it contains outdated references, links, priorities, or workflow notes
- it appears to duplicate content now maintained elsewhere
- no one can clearly explain whether it is still active, reference-only, or obsolete

### Stale-content response

When a file appears stale, review it and choose one of the following actions:

- update it and keep it active
- trim it and convert repeated material to cross-references
- mark it as `Superseded` if a newer authoritative file exists
- move it to `Archive/` if it no longer supports current work or current understanding

### Stale-content rule

A file should not remain in the active structure indefinitely without review just because it is not causing immediate problems.  
If it is stale, unclear, duplicated, or no longer useful, it should be reviewed and resolved.

---

## Practical Review Sequence

When conducting a review, use this sequence:

1. confirm whether the file still serves a current purpose
2. confirm whether the content still belongs in that file
3. confirm whether metadata is accurate
4. confirm whether related file links still make sense
5. confirm whether any repeated content should be reduced to a summary or cross-reference
6. decide whether the file should remain active, be marked superseded, or be archived

---

## Operating Principle

Maintain for trust, not for volume.

The goal is not to update files constantly.  
The goal is to keep active files reliable enough to support real use, real decisions, and real work.

A file is healthy when it is:
- current enough to trust
- clear enough to use
- scoped well enough to avoid duplication
- reviewed often enough to avoid silent drift


