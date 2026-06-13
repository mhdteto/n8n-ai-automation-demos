# Setup Guide

## Requirements

- n8n account or self-hosted n8n instance
- Test data only for first import
- Credentials configured inside n8n, not inside exported JSON files

## Import steps

1. Open n8n.
2. Create a new workflow.
3. Select import from file.
4. Upload one JSON file from the `workflows` folder.
5. Review every node before activating the workflow.
6. Replace sample nodes with your production tools.
7. Add credentials inside n8n.
8. Test with safe sample data.

## Safety rules

- Do not publish API keys.
- Do not publish tokens.
- Do not publish passwords.
- Do not use real customer data in public demos.
- Keep human review for outbound emails and CRM updates.

## Production notes

Before using a workflow in production, add:

- Error handling
- Logging
- Data retention rules
- Manual approval where needed
- Clear ownership for failures
