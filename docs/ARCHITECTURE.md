# Architecture

## Role
This repository is the Google Workspace bridge for the XPS platform.

It converts approved runtime actions into Google-native collaboration artifacts while keeping canonical truth in the runtime and intelligence systems.

## Allowed responsibilities
- Drive scaffolding
- Shared Drive and folder topology management
- Sheets mirrors
- Calendar orchestration
- Gmail summaries and draft generation
- Docs generation from approved templates
- lightweight webhook bridge logic
- Apps Script helpers where they reduce friction without taking ownership of truth

## Forbidden
- primary ingestion engine
- primary CRM sync
- primary data warehouse
- primary auth
- canonical lead truth
- canonical score or recommendation authority

## Upstream systems
- `xps-intelligence-system`
- `xps-intel`
- `xps-distallation-system`
- `xps-intelligence-control-plane`

## Downstream Google surfaces
- Gmail
- Calendar
- Drive
- Docs
- Sheets
