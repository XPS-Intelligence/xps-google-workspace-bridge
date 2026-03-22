# Workspace Matchup

## Best Google Workspace matchup for the XPS platform

### Gmail
- outbound AI-assisted email drafts
- inbound lead reply ingestion
- manager and owner digest delivery
- notification fallback channel for high-priority system alerts

### Calendar
- follow-up reminders
- lead next-step scheduling
- owner and manager briefing cadence
- proactive agent reminders constrained by user settings and quiet hours

### Drive
- canonical document vault for SOPs, playbooks, approved templates, collateral, and exported reports
- operator-visible artifact storage for summaries, audit exports, and benchmark packs
- controlled folder hierarchy generated from the runtime and control-plane manifests

### Docs
- SOP generation
- account plans
- lead intelligence reports
- owner and manager briefings
- proposal and notes drafting

### Sheets
- lightweight mirrored reporting
- human-auditable scorecards
- promo-code planning
- benchmark exports

### Apps Script / Webhooks
- lightweight bridge automation only
- approved webhook fanout into Gmail, Calendar, Sheets, and Drive
- no primary truth ownership

## What Google Workspace should not own
- primary auth
- primary lead truth
- canonical crawl or validation data
- entity resolution authority
- CRM activation authority
- runtime queue state

## Repository alignment
- `xps-intelligence-system`: users, roles, auth, CRM workflow, assistant runtime, operator actions
- `xps-intel`: domain taxonomy, seed intelligence, retrieval artifacts, distilled knowledge
- `xps-distallation-system`: validation, confidence, normalization, freshness, packaging
- `xps-google-workspace-bridge`: Google-facing document, messaging, calendar, and artifact bridges
- `xps-vision`: discovery, research, and demo/report surfaces using the same bridge patterns
