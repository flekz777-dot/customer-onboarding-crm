# Customer Onboarding CRM

Automated customer onboarding workflow that guides new clients through a structured sequence — from first contact to week 1 completion.

## Result
**80% reduction in manual handoffs.** Team notified automatically at each stage, no manual follow-up needed.

## How it works

1. New customer webhook triggers the workflow
2. Required fields validated — error alert sent if missing
3. HubSpot contact created automatically
4. Team notified via Telegram
5. Welcome email sent via Gmail
6. Wait 2 hours → follow-up email sent
7. Wait 1 day → HubSpot CRM status updated
8. Additional follow-up emails sent over next 2 days
9. Week 1 marked complete in HubSpot
10. Team notified of completion via Telegram

## Tech Stack

| Tool | Purpose |
|---|---|
| n8n | Workflow orchestration |
| HubSpot | CRM contact & deal management |
| Gmail | Automated email sequence |
| Telegram Bot API | Team notifications & alerts |

## Key Features

- **Validation layer** — catches missing data before processing
- **Multi-step sequence** — timed delays for natural communication flow
- **Error handling** — instant Telegram alert if validation fails
- **CRM sync** — HubSpot updated automatically at each milestone

## Business Impact

- 80% reduction in manual handoffs between team members
- Consistent onboarding experience for every customer
- Zero missed follow-ups through automated sequencing
