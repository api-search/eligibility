---
api_specs:
- filename: competitortracker-io-openapi-generated.yml
  format: yaml
  label: Competitor Tracker & Co. API
  slug: competitortracker-io-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/competitortracker-io/openapi/_ae-authored/competitortracker-io-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: made between you, whether personally or on behalf of an entity
    type: individual
  minimum_age:
    text: The Site is intended for users who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Commercial endeavors not approved
    text: The Site may not be used in connection with any commercial endeavors except those that are specifically endorsed or approved by us.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may be required to register with the Site, request an invite, or provide information needed to open or manage a case.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Competitor Tracker & Co.
provenance_date: '2026-11-09'
provider_name: Competitor Tracker & Co.
provider_slug: competitortracker-io
slug: competitortracker-io-eligibility
source_date: '2026-11-09'
source_filename: competitortracker-io-eligibility.yml
source_heading: Eligibility
source_page: https://competitortracker.io/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Competitor Tracker & Co.\naid: competitortracker-io\nurl: https://competitortracker.io/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: made between you, whether personally or on behalf of an entity\nrestricted_uses:\n- summary: Commercial endeavors not approved\n  text: The Site may not be used in connection with any commercial endeavors except those that are specifically\n    endorsed or approved by us.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may be required to register with\
  \ the Site, request an invite, or provide information needed to open\n    or manage a case.\nminimum_age:\n  value: '18'\n  text: The Site is intended for users who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/competitortracker-io/eligibility/competitortracker-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Competitor Tracker & Co.'s own page on 2026-11-09.
synthetic: false
tags:
- Company
- Competitive Intelligence
- Competitor Tracking
- Website Change Monitoring
- Price Monitoring
- Market Intelligence
- MCP
- AI Agents
---
