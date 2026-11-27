---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Service on behalf of an organization, you represent that you are authorized to bind it.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No PHI / HIPAA data
    text: Do not send or retrieve protected health information (PHI) under HIPAA through any usefulapi server.
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
name: usefulapi-io
provenance_date: '2026-11-10'
provider_name: usefulapi-io
provider_slug: usefulapi-io
slug: usefulapi-io-eligibility
source_date: '2026-11-10'
source_filename: usefulapi-io-eligibility.yml
source_heading: Eligibility
source_page: https://usefulapi.io/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: usefulapi-io\naid: usefulapi-io\nurl: https://usefulapi.io/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Service on behalf of an organization, you represent that you are authorized to bind it.\nrestricted_uses:\n- summary: No PHI / HIPAA data\n  text: Do not send or retrieve protected health information (PHI) under HIPAA through any usefulapi server.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/usefulapi-io/eligibility/usefulapi-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from usefulapi-io's own page on 2026-11-10.
synthetic: false
tags:
- Company
- MCP
- Software-as-a-Service
- API Hosting
- Developer Tools
---
