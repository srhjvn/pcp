
````md
---
status: Draft
last_updated: 2026-04-06
related_files:
  - [README.md](README.md)
  - [OperatingRhythm.md](OperatingRhythm.md)
  - [PreferencesAndConstraints.md](PreferencesAndConstraints.md)
  - [DecisionLog.md](DecisionLog.md)
  - [CurrentProjects.md](CurrentProjects.md)
review_date: 2026-07-06
---

# Template Library

This file owns the catalog of active templates used to create, maintain, and govern documentation within the Personal Context Portfolio.

## Purpose

The Template Library provides a single reference point for the templates currently in use across the repository. Its purpose is to make template usage consistent, reduce reinvention, and support maintainable documentation as the portfolio grows.

Each template entry should identify:
- the purpose of the template
- the source file or governing file associated with it
- the expected output or use case
- when the template should be used

This library is intended to track active templates only. Retired or replaced templates should either be removed or marked as superseded if historical reference is still useful.

---

## Active Templates

## 1. File Metadata Block

### Purpose
Provides a standard metadata block for new and updated files so status, review timing, and file relationships remain consistent across the repository.

### Template

```md
---
status: Draft
last_updated: YYYY-MM-DD
related_files: [README.md]
review_date: YYYY-MM-DD
---
````

### Source files

* `README.md`
* `PreferencesAndConstraints.md`

### Output / use case

Use at the top of all new files and add to older files as they are updated.

---

## 2. File Ownership Statement

### Purpose

Defines, in one sentence, what a file owns so boundaries remain clear and overlap is easier to detect during maintenance.

### Template

```md
This file owns the [subject, function, or system purpose] for the Personal Context Portfolio.
```

### Source files

* `README.md`
* each core file using the ownership convention

### Output / use case

Use directly below the file title in core files and governance files.

---

## 3. Single-Source-of-Truth Rule Pattern

### Purpose

Provides the standard structure for documenting where information should live, how duplication should be handled, and when cross-references should be used instead of repetition.

### Template structure

* primary ownership by file
* duplication rules
* cross-reference guidance
* maintenance rule
* conflict resolution rule

### Source files

* `README.md`
* governance sections referencing repository structure

### Output / use case

Use when defining or revising governance rules related to file ownership, duplication control, or content boundaries.

---

## 4. Related Files Convention

### Purpose

Provides a consistent way to show which files have a direct working relationship to the current file.

### Template

```md
related_files: [README.md, CurrentProjects.md, DecisionLog.md]
```

### Source files

* `README.md`
* file metadata standard

### Output / use case

Use in file metadata to identify directly connected source, summary, dependency, or companion files.

---

## 5. Archive Rule Pattern

### Purpose

Provides the standard structure for deciding when content should remain active, stay visible as reference, or move to archive.

### Template structure

* archive criteria
* inactive vs. reference distinction
* naming and location convention
* status guidance
* practical maintenance guidance

### Source files

* `README.md`
* archive rules section

### Output / use case

Use when evaluating whether a file should remain active, be marked superseded, or move to `Archive/`.

---

## 6. Operating Rhythm Pattern

### Purpose

Provides the standard structure for defining review cadence, update triggers, and stale-content handling.

### Template structure

* purpose
* weekly review rhythm
* monthly review rhythm
* update triggers
* stale-content review rule
* practical review sequence
* operating principle

### Source files

* `OperatingRhythm.md`
* `README.md`

### Output / use case

Use for maintenance workflow design and ongoing repository review practice.

---

## 7. Overlap and Drift Cleanup Checklist

### Purpose

Provides a repeatable checklist for auditing duplication, boundary confusion, and cleanup needs across the repository.

### Template structure

* objective
* review and cleanup tasks
* completion standard

### Source files

* `README.md`
* review work items related to maintenance or cleanup

### Output / use case

Use when reviewing the repository for duplicate topics, unclear boundaries, or drift between files.

---

## 8. Governance Section Pattern

### Purpose

Provides a consistent format for writing governance sections so rules are documented in a predictable and readable way.

### Template structure

* purpose or framing paragraph
* rule categories
* practical guidance
* operating principle

### Source files

* `README.md`
* governance-oriented files

### Output / use case

Use when drafting new governance sections for maintenance, structure, ownership, archive rules, or workflow rules.

---

## 9. Review Checklist Pattern

### Purpose

Provides a simple repeatable structure for converting governance or audit work into actionable checklist form.

### Template structure

* objective
* task list
* completion criteria
* optional short-form version

### Source files

* `OperatingRhythm.md`
* review and cleanup work items

### Output / use case

Use when translating governance standards into a working review list for recurring maintenance.

---

## 10. Template Entry Pattern

### Purpose

Provides the standard format for documenting templates inside this library so the template catalog stays consistent over time.

### Template structure

* template name
* purpose
* template or structure
* source files
* output / use case

### Source files

* `TemplateLibrary.md`

### Output / use case

Use whenever a new active template is added to this file.

---

## Use Guidance

Add a template to this library when:

* it is actively reused across files or workflows
* it defines a recurring documentation pattern
* it supports governance, maintenance, or repository consistency
* it would be helpful to reference again rather than recreate manually

Do not add a template when:

* it was used only once
* it is still exploratory and not yet adopted
* it duplicates another active template already listed here

---

## Maintenance Rule

This file should be reviewed whenever:

* a new recurring template is adopted
* an existing template is replaced or retired
* governance changes alter how templates are used
* a review finds repeated manual patterns that should become templates

Retired templates should be removed or marked `Superseded` if historical context is still useful.

---

## Operating Principle

Document the patterns that are actually being reused.

The goal of the template library is not to collect every possible format.
The goal is to preserve the templates that make the repository easier to maintain, easier to extend, and easier to use consistently.

```

## Notes on the current active template set

Based on the work completed so far, the strongest candidates for “active templates” are:
- metadata block
- ownership statement
- related files convention
- governance section pattern
- archive rule pattern
- operating rhythm pattern
- review checklist pattern

```
