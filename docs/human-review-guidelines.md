# Human Review Guidelines

## Overview

AI automation should support human decision-making.

For many SMB workflows, the safest approach is human-in-the-loop automation.

This means the workflow prepares, classifies or summarizes information, but a human validates the output before action is taken.

---

## When human review is required

Human review is strongly recommended when the workflow produces:

- Customer-facing messages.
- Sales recommendations.
- CRM updates.
- Lead scoring.
- Support prioritization.
- Legal, financial or contractual summaries.
- Content ready for publication.
- Any decision that affects a customer relationship.

---

## What reviewers should check

Reviewers should verify:

- Accuracy.
- Tone.
- Context.
- Missing information.
- Incorrect assumptions.
- Sensitive data exposure.
- Customer impact.
- Business relevance.
- Compliance with internal policies.

---

## Recommended review statuses

Use simple review statuses:

```txt
approved
needs_edit
rejected
needs_more_context
```

---

## Example review flow

1. Workflow receives input.
2. AI generates classification, summary or recommendation.
3. Output is sent to a human reviewer.
4. Reviewer approves or edits the output.
5. Final output is sent to CRM, email, Slack, task manager or content system.

---

## Best practice

Start with review-heavy workflows.

Reduce manual checks only after the workflow has been tested, measured and trusted over time.
