# System Map

## Position in the platform

```mermaid
flowchart LR
  CP["xps-intelligence-control-plane"] --> RUNTIME["xps-intelligence-system"]
  INTEL["xps-intel"] --> RUNTIME
  DIST["xps-distallation-system"] --> INTEL
  DIST --> RUNTIME
  RUNTIME --> GW["xps-google-workspace-bridge"]
  GW --> GMAIL["Gmail"]
  GW --> GCAL["Calendar"]
  GW --> GDRIVE["Drive"]
  GW --> GDOCS["Docs"]
  GW --> GSHEETS["Sheets"]
  GW --> VISION["xps-vision"]
```

## Operational model
- runtime decides what should happen
- workspace bridge turns approved actions into Google-native artifacts
- intelligence and distallation systems remain the truth engines
