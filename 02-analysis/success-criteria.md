# Success Criteria

Success criteria are how you prove your final system succeeded.

## Why this matters

If criteria are vague now, evaluation will be weak later.

## Make criteria measurable

Each criterion should include:

- a clear condition
- a measurable threshold (time/count/percentage/pass condition)
- how it will be tested
- linked requirement ID(s)

## Vague vs measurable

### Vague

- The system should be easy to use.
- The program should run quickly.

### Measurable

- A trained staff user can add a new record in **30 seconds or less**.
- Search returns results in **under 2 seconds** for **500 records**.
- Duplicate booking attempts are blocked in **100% of test cases**.

## Example criteria table

| SC ID | Linked requirement(s) | Measurable criterion | Test method | Evidence needed |
|---|---|---|---|---|
| SC1 | R1 | Duplicate entries are blocked in 100% of normal and boundary test cases. | System tests ST-04 to ST-09 | Test logs + screenshots |
| SC2 | R2 | User can retrieve a record by surname in under 2 seconds for 500 records. | Timed performance test | Timed test table |
| SC3 | R3 | 4 out of 5 stakeholder tasks are completed without help by 80% of test users. | Usability test | Task completion sheet |

## Final check before leaving Analysis

Use: [Success Criteria Checklist](templates/success-criteria-checklist.md)
