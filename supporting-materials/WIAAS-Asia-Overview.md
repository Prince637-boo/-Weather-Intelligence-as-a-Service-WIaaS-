# WIAAS Asia - Supporting Overview

## What it is

WIAAS Asia (Weather Intelligence as a Service) turns live weather and climate signals into operational decisions for agriculture, infrastructure, logistics, and emergency response across Asia.

## Why it matters

Most weather tools stop at forecast numbers. WIAAS connects those numbers to consequences: crop water stress, fungal risk, grid cooling pressure, logistics exposure, and crisis response actions.

## How it works

1. FastAPI ingests live regional telemetry and seven-day forecast fields.
2. Deterministic physics calculates VPD, heat index, wet-bulb conditions, resource ledgers, and risk.
3. The WIaaS multi-agent workflow produces Research, Agriculture, Grid, and Logistics analysis.
4. CrisisLens provides multi-hazard threat intelligence and public-safety guidance.
5. The frontend presents a region-aware map, dashboards, bilingual chat, and practical next steps.

## Regional intelligence

Every response preserves the selected region through `region_key`, `region_name`, `region_context`, telemetry, climate matrix, resource ledger, risk level, and mission criticality score. Agriculture requests can use seven-day maximum and minimum temperatures, precipitation totals, and rain-probability arrays for day-by-day plans.

## Suggested demonstration questions

- Generate a full WIaaS report for Karachi.
- What should farmers do in Karachi over the next 7 days?
- What is the current grid and logistics risk in Lahore?
- Give me an evidence-based public safety assessment for Kathmandu.
- What threats are active near Multan?
- What can CrisisLens do?

## Run locally

```text
python run.py
```

Open `http://127.0.0.1:8000` and select a city from Asia Monitoring Network.

## Included files

- `about-us.mp4` - product demonstration video.
- `wiaas_workflow_architecture.svg` - WIaaS decision graph.
- `crisislens_workflow_architecture.svg` - CrisisLens threat graph.

Repository: https://github.com/abdxllxh/WIaaS-Asia
