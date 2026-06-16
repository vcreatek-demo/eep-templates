# ${{ values.project_title }}

**Client:** ${{ values.client_name }}
**Owner:** ${{ values.owner_name }}
**Status:** ${{ values.lifecycle }}

## About

${{ values.project_description }}

## Documentation

This repository contains project documentation only.
The project code lives in the client environment.

Documentation is published automatically to the vCreatek EEP portal.

## Structure

docs/

├── index.md          ← Project overview — start here

├── architecture.md   ← System architecture and design

├── runbook/          ← Operations and troubleshooting

├── decisions/        ← Architecture decision records

└── handover/         ← Client handover documentation

## How to Update Docs

1. Clone this repo
2. Edit files in the `docs/` folder
3. Push to main
4. EEP updates automatically within 30 minutes
   Or click Refresh in the EEP catalog entry