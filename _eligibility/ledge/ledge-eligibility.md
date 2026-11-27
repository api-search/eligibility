---
api_specs:
- filename: ledge-sources-api-openapi.yml
  format: yaml
  label: Ledge Sources API
  slug: ledge-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ledge/openapi/ledge-sources-api-openapi.yml
- filename: ledge-transactions-api-openapi.yml
  format: yaml
  label: Ledge Transactions API
  slug: ledge-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ledge/openapi/ledge-transactions-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Harvesting personal data
    text: harvest or collect personally identifiable information about users without their express consent
  - summary: Malicious code
    text: transmit or otherwise make available any malicious code, including any virus, worm, trojan horse, time bomb, web bug, spyware
  - summary: Interference with the website
    text: interfere with or disrupt the integrity, performance or operation of the Website
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
name: Ledge
provenance_date: '2026-11-09'
provider_name: Ledge
provider_slug: ledge
slug: ledge-eligibility
source_date: '2026-11-09'
source_filename: ledge-eligibility.yml
source_heading: Eligibility
source_page: https://www.ledge.co/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ledge\naid: ledge\nurl: https://www.ledge.co/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Harvesting personal data\n  text: harvest or collect personally identifiable information about users without their express consent\n- summary: Malicious code\n  text: transmit or otherwise make available any malicious code, including any virus, worm, trojan horse, time bomb,\n    web bug, spyware\n- summary: Interference with the website\n  text: interfere with or disrupt the integrity, performance or operation of the Website\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ledge/eligibility/ledge-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 3 quoted statements, read from Ledge's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Accounting
- Reconciliation
- Financial Close
- Payment Operations
- Transaction Matching
- Cash Application
- Journal Entries
- AI Agents
- ERP Integration
- Finance Automation
---
