# Hypothesis Logbook

Use this reference when documenting, updating, or reviewing hypothesis tests in a spreadsheet or testing tracker.

## Suggested Columns

Use these fields when creating or updating a hypothesis log:

* Hypothesis ID
* Date Created
* Status
* User (specific)
* Scene
* Job Statement
* Outcome Type
* Current Alternative
* Pain Level (1-10)
* Pain Evidence
* Riskiest Assumption
* Hypothesis Statement
* Confirm Threshold
* Kill Condition
* Test Designed
* Test Start Date
* Test End Date
* Result
* Outcome
* Next Hypothesis ID
* Notes

## Documentation Rules

* Preserve the user's testing log as the source of record when the user asks to track ongoing testing.
* Add a new row for each distinct falsifiable hypothesis.
* Keep each row specific enough that the test can be interpreted later without chat context.
* Use short, evidence-based wording. Avoid pitch copy.
* Use explicit dates when known. If dates are unknown, ask or leave them blank rather than inventing them.
* Treat a kill condition as required. If there is no kill condition, return to the hypothesis workshop.

## Status and Outcome Guidance

Use clear statuses such as:

* `Draft` - hypothesis is not ready because the user, behavior, threshold, or kill condition is missing.
* `Ready` - hypothesis and test are defined but not started.
* `Testing` - test is currently running.
* `Complete` - result has been recorded.
* `Parked` - not actively being tested.

Use clear outcomes such as:

* `Confirmed`
* `Invalidated`
* `Inconclusive`
* `Pivot`
* `Needs follow-up`

## Row-Ready Output

Before editing the workbook, show the proposed row in this format:

```markdown
Hypothesis ID:
Date Created:
Status:
User (specific):
Scene:
Job Statement:
Outcome Type:
Current Alternative:
Pain Level (1-10):
Pain Evidence:
Riskiest Assumption:
Hypothesis Statement:
Confirm Threshold:
Kill Condition:
Test Designed:
Test Start Date:
Test End Date:
Result:
Outcome:
Next Hypothesis ID:
Notes:
```

If editing a workbook or spreadsheet directly, preserve existing rows and formulas/styles where practical.