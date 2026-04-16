# Requirements Specification

This is the backbone of your project. Every requirement should come from evidence.

## What a good requirement looks like

A requirement should be:

- specific
- testable
- justified
- linked to research and stakeholder evidence
- numbered (R1, R2, R3...)

Use: [Requirements Template](templates/requirements-template.md)

## Recommended requirement format

| ID | Requirement | Type | Priority | Stakeholder(s) | Evidence source | Justification |
|---|---|---|---|---|---|---|
| R1 | The system shall prevent duplicate equipment loans for the same item at the same time. | Functional | Must | PE staff | Interview 2026-10-03, Survey Q4 | Duplicate loans were identified as the main operational issue. |

## Model requirement entry

- **ID:** R2  
- **Requirement:** The system shall allow staff to search loan records by student surname and return all matches within 2 seconds for a dataset of at least 500 records.  
- **Type:** Functional + performance  
- **Priority:** Must  
- **Stakeholder(s):** PE staff lead  
- **Evidence:** Interview notes + existing product research  
- **Justification:** Staff currently lose lesson time manually checking paper records.

## Weak vs strong requirements

### Weak

- “Good UI”
- “Fast search”
- “Secure system”

### Strong

- “Users can complete new booking in 4 inputs or fewer.”
- “Search returns matching records in under 2 seconds for 500 records.”
- “Only authenticated staff accounts can edit records.”

## Requirement quality checks

Before moving on, check each requirement:

- Is it clear enough to test later?
- Can I point to evidence for it?
- Is the scope realistic for my NEA?
- Have I avoided duplicate or overlapping requirements?
