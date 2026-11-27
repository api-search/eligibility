---
api_specs:
- filename: millimetric-identity-api-openapi.yml
  format: yaml
  label: Millimetric Identity API
  slug: millimetric-identity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/millimetric/openapi/millimetric-identity-api-openapi.yml
- filename: millimetric-ingest-api-openapi.yml
  format: yaml
  label: Millimetric Ingest API
  slug: millimetric-ingest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/millimetric/openapi/millimetric-ingest-api-openapi.yml
- filename: millimetric-read-api-openapi.yml
  format: yaml
  label: Millimetric Read API
  slug: millimetric-read-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/millimetric/openapi/millimetric-read-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old (or of legal age in your jurisdiction) to use the Service.
    type: individual
  minimum_age:
    text: You must be at least 18 years old (or of legal age in your jurisdiction) to use the Service.
    value: '18'
  restricted_uses:
  - summary: Tracking without informed notice
    text: don't use Millimetric to track people who haven't been informed it's happening
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
name: Millimetric
provenance_date: '2026-11-10'
provider_name: Millimetric
provider_slug: millimetric
slug: millimetric-eligibility
source_date: '2026-11-10'
source_filename: millimetric-eligibility.yml
source_heading: Eligibility
source_page: https://www.millimetric.ai/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Millimetric\naid: millimetric\nurl: https://www.millimetric.ai/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old (or of legal age in your jurisdiction) to use the Service.\nrestricted_uses:\n- summary: Tracking without informed notice\n  text: don't use Millimetric to track people who haven't been informed it's happening\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old (or of legal age\
  \ in your jurisdiction) to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/millimetric/eligibility/millimetric-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Millimetric's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Analytics
- Web Analytics
- Product Analytics
- Attribution
- Privacy
- MCP
- AI Agents
- Event
- Developer Tools
---
