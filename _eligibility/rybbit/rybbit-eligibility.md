---
api_specs:
- filename: rybbit-analytics-api-openapi.yml
  format: yaml
  label: Rybbit Analytics API
  slug: rybbit-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rybbit/openapi/rybbit-analytics-api-openapi.yml
- filename: rybbit-event-tracking-api-openapi.yml
  format: yaml
  label: Rybbit Event Tracking API
  slug: rybbit-event-tracking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rybbit/openapi/rybbit-event-tracking-api-openapi.yml
- filename: rybbit-sessions-api-openapi.yml
  format: yaml
  label: Rybbit Sessions API
  slug: rybbit-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rybbit/openapi/rybbit-sessions-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'For cloud service users: You must be a human - accounts registered by bots or automated methods are not permitted'
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Collecting PII without consent
    text: Use the service to collect personally identifiable information without proper consent
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
name: Rybbit
provenance_date: '2026-11-10'
provider_name: Rybbit
provider_slug: rybbit
slug: rybbit-eligibility
source_date: '2026-11-10'
source_filename: rybbit-eligibility.yml
source_heading: Eligibility
source_page: https://rybbit.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rybbit\naid: rybbit\nurl: https://rybbit.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'For cloud service users: You must be a human - accounts registered by bots or automated methods are not\n    permitted'\nrestricted_uses:\n- summary: Collecting PII without consent\n  text: Use the service to collect personally identifiable information without proper consent\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/rybbit/eligibility/rybbit-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Rybbit's own page on 2026-11-10.
synthetic: false
tags:
- Analytics
- Web Analytics
- Product Analytics
- Privacy
- Open Source
- Cookieless
---
