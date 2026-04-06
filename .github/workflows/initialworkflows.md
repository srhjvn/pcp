---
status: Draft
last_updated: 2026-04-06
related_files:
  - [README.md](README.md)
  - [OperatingRhythm.md](OperatingRhythm.md)
  - [TemplateLibrary.md](TemplateLibrary.md)
  - [CurrentProjects.md](CurrentProjects.md)
  - [DecisionLog.md](DecisionLog.md)
  - [PCPMaint.yml](.github/workflows/PCPMaint.yml)
review_date: 2026-07-06
---

# Initial Workflows

This file owns the common maintenance workflows used to keep the Personal Context Portfolio current, consistent, and operational.

## Purpose

The Personal Context Portfolio is intended to function as living documentation. This file defines the most common recurring workflows used to maintain the repository, reduce drift, and keep core files aligned with current work and current understanding.

Each workflow includes:
- a defined purpose
- linked source files
- a start condition
- an end condition
- a practical sequence of steps

These workflows are intended to be lightweight and repeatable. They are not meant to create unnecessary overhead.

---

## Workflow 1: Weekly Active Review

### Purpose
Review active priorities, projects, and recent decisions to keep current files aligned with actual work.

### Source files
- [GoalsAndPriorities.md](GoalsAndPriorities.md)
- [CurrentProjects.md](CurrentProjects.md)
- [DecisionLog.md](DecisionLog.md)
- [OperatingRhythm.md](OperatingRhythm.md)

### Start condition
Begin when the weekly review checkpoint is reached or when a week of active work has meaningfully changed current priorities, project status, or decisions.

### End condition
End when current priorities, active project status, and any meaningful decisions have been reviewed and updated as needed.

### Steps
1. Review `GoalsAndPriorities.md` for changes in focus or sequencing
2. Review `CurrentProjects.md` for current status, next steps, and active relevance
3. Review recent work for decisions that belong in `DecisionLog.md`
4. Add or revise content where needed
5. Confirm that cross-references remain accurate
6. Leave unchanged files untouched if no meaningful update is needed

---

## Workflow 2: Monthly Structural Review

### Purpose
Review the repository at a structural level to identify overlap, drift, stale content, or archive candidates.

### Source files
- [README.md](README.md)
- [OperatingRhythm.md](OperatingRhythm.md)
- [DecisionLog.md](DecisionLog.md)
- [TemplateLibrary.md](TemplateLibrary.md)
- all core portfolio files

### Start condition
Begin when the monthly review checkpoint is reached or when the repository has undergone enough change that structure should be rechecked.

### End condition
End when file boundaries, metadata, cross-references, and archive decisions have been reviewed and any necessary cleanup items have been captured or completed.

### Steps
1. Review file ownership statements across the core file set
2. Check for duplicated or drifting content
3. Confirm metadata accuracy and review dates
4. Confirm `related_files` still reflect actual working relationships
5. Identify any files that should be marked `Superseded` or moved to `Archive/`
6. Record any structural clarifications in `DecisionLog.md` if needed

---

## Workflow 3: Event-Triggered Update

### Purpose
Update the portfolio when a meaningful change happens between scheduled reviews.

### Source files
- [CurrentProjects.md](CurrentProjects.md)
- [GoalsAndPriorities.md](GoalsAndPriorities.md)
- [DecisionLog.md](DecisionLog.md)
- [PreferencesAndConstraints.md](PreferencesAndConstraints.md)
- any directly affected file

### Start condition
Begin when a meaningful decision, priority change, project change, workflow change, or structural change occurs.

### End condition
End when the affected file or files reflect the current reality and any related source-of-truth updates have been made.

### Steps
1. Identify the file that owns the changed subject
2. Update the source file first
3. Update related summary files only if needed
4. Add the decision to `DecisionLog.md` if the change is meaningful
5. Adjust metadata fields as appropriate
6. Confirm that the change does not create duplication elsewhere

---

## Workflow 4: New File Creation

### Purpose
Create a new file in a way that is consistent with repository standards and avoids unnecessary duplication.

### Source files
- [README.md](README.md)
- [TemplateLibrary.md](TemplateLibrary.md)
- [PreferencesAndConstraints.md](PreferencesAndConstraints.md)
- [OperatingRhythm.md](OperatingRhythm.md)

### Start condition
Begin when new content cannot be cleanly maintained within an existing file and a new file is justified.

### End condition
End when the new file has metadata, an ownership statement, related file links, and a clear place in the repository structure.

### Steps
1. Confirm that the content does not already belong in an existing file
2. Create the file using the metadata block template
3. Add a one-line ownership statement
4. Define the file’s purpose and scope
5. Add `related_files`
6. Link the file from `README.md` if appropriate
7. Confirm the new file does not duplicate another file’s purpose

---

## Workflow 5: Overlap and Drift Cleanup

### Purpose
Reduce duplication and reinforce file boundaries when overlap or unclear ownership is discovered.

### Source files
- [README.md](README.md)
- [TemplateLibrary.md](TemplateLibrary.md)
- [OperatingRhythm.md](OperatingRhythm.md)
- affected core files

### Start condition
Begin when duplicate topics, unclear boundaries, or repeated content are identified.

### End condition
End when one authoritative source has been confirmed for the overlapping content and repeated material has been removed, trimmed, or converted to cross-references.

### Steps
1. Identify the overlapping content
2. Decide which file owns the subject
3. Keep the full content in the owning file
4. Remove or shorten repeated versions in other files
5. Replace repeated content with summary language or cross-reference links
6. Update `related_files` if the cleanup changes working relationships

---

## Workflow 6: Archive Review

### Purpose
Move outdated or no-longer-useful material out of the active structure while preserving useful history when appropriate.

### Source files
- [README.md](README.md)
- [OperatingRhythm.md](OperatingRhythm.md)
- [DecisionLog.md](DecisionLog.md)
- [Archive/](Archive/)
- affected file

### Start condition
Begin when a file no longer supports current work, current understanding, or active reference use.

### End condition
End when the file has been reviewed and one of the following is true: it remains active, is marked `Superseded`, or is moved to `Archive/`.

### Steps
1. Review the file against archive criteria
2. Decide whether it is still active, still useful as reference, or historical only
3. Update metadata as needed
4. Move the file to `Archive/` if appropriate
5. Retain original filename unless version distinction is needed
6. Update links or references if the file location changes

---

## Workflow 7: Template Update or Addition

### Purpose
Keep the template library aligned with actual repeatable patterns used in the repository.

### Source files
- [TemplateLibrary.md](TemplateLibrary.md)
- [README.md](README.md)
- [OperatingRhythm.md](OperatingRhythm.md)

### Start condition
Begin when a new recurring documentation pattern is adopted or an existing template is replaced or revised.

### End condition
End when the active template is documented in `TemplateLibrary.md` and any superseded template treatment is clear.

### Steps
1. Confirm the pattern is actually reusable
2. Add or revise the template entry in `TemplateLibrary.md`
3. Define purpose, source files, and output/use case
4. Remove or mark superseded template entries if needed
5. Confirm the template supports current repo standards

---

## Workflow 8: Maintenance Automation Review

### Purpose
Keep the GitHub maintenance workflow aligned with the documentation standards used in the repository.

### Source files
- [.github/workflows/PCPMaint.yml](.github/workflows/PCPMaint.yml)
- [README.md](README.md)
- [OperatingRhythm.md](OperatingRhythm.md)
- [TemplateLibrary.md](TemplateLibrary.md)

### Start condition
Begin when repository standards change, automation warnings become inaccurate, or the GitHub Action no longer reflects current file conventions.

### End condition
End when the automation checks and reminder prompts match the current repository standards and file set.

### Steps
1. Review the active repository standards
2. Review `PCPMaint.yml`
3. Identify outdated checks, file lists, or prompts
4. Update validation logic to match current metadata conventions
5. Add new governed files if needed
6. Test the workflow and confirm it produces useful guidance

---

## Use Guidance

These workflows are intended to support the most common maintenance actions in the repository.  
Use the lightest workflow that resolves the actual need.

Do not treat every change as a full review cycle.  
Use event-triggered updates for meaningful changes between scheduled reviews, and use broader reviews only when the structure or system needs attention.

---

## Operating Principle

Use workflows to preserve clarity, not to create ceremony.

A workflow is successful when it helps the repository stay current, reduces ambiguity, and supports consistent maintenance without unnecessary repetition.
