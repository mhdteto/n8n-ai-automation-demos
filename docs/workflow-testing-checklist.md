# Workflow Testing Checklist

Use this checklist before activating any workflow.

## Workflow structure

- [ ] The workflow imports correctly into n8n.
- [ ] All nodes are named clearly.
- [ ] Placeholder nodes are replaced or documented.
- [ ] The workflow has a clear start and end.
- [ ] The output is easy to inspect.

## Credentials

- [ ] No credentials are stored in the JSON file.
- [ ] Credentials are configured inside n8n.
- [ ] Test credentials are used before production credentials.
- [ ] Access permissions are limited.

## Data safety

- [ ] No real customer data is used during initial testing.
- [ ] No confidential data is hardcoded.
- [ ] Inputs are validated.
- [ ] Sensitive fields are removed when not needed.

## AI output

- [ ] The prompt is clear.
- [ ] The output format is structured.
- [ ] The model is not asked to make unsupported claims.
- [ ] The output is reviewed by a human.
- [ ] Edge cases are tested.

## Error handling

- [ ] Failed executions are visible.
- [ ] Notifications are configured for failures.
- [ ] Manual fallback is defined.
- [ ] Duplicate submissions are considered.
- [ ] Rate limits are considered.

## Business readiness

- [ ] The use case has clear business value.
- [ ] The workflow saves time or reduces manual sorting.
- [ ] The workflow does not automate high-risk decisions without review.
- [ ] The owner of the workflow is defined.
- [ ] The workflow can be monitored after activation.
