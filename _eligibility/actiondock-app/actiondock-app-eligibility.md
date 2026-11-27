---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and legally able to enter this agreement.
    type: individual
  - text: Business users represent that they have authority to bind their organization.
    type: business
  minimum_age:
    text: You must be at least 18 years old and legally able to enter this agreement.
    value: '18'
  restricted_uses:
  - summary: No regulated advice
    text: ActionDock does not provide legal, financial, medical, employment, credit, or other regulated advice
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: actiondock-app
provenance_date: '2026-11-09'
provider_name: actiondock-app
provider_slug: actiondock-app
slug: actiondock-app-eligibility
source_date: '2026-11-09'
source_filename: actiondock-app-eligibility.yml
source_heading: Eligibility
source_page: https://actiondock.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: actiondock-app\naid: actiondock-app\nurl: https://actiondock.app/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and legally able to enter this agreement.\n- type: business\n  text: Business users represent that they have authority to bind their organization.\nrestricted_uses:\n- summary: No regulated advice\n  text: ActionDock does not provide legal, financial, medical, employment, credit, or other regulated advice\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and legally able to enter this agreement.\n"
source_yaml_url: https://artifacts.apis.io/actiondock-app/eligibility/actiondock-app-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from actiondock-app's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- MCP
- Gateways
- Human-in-the-Loop
---
