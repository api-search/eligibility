---
api_specs:
- filename: ugcagent-messages-api-openapi.yml
  format: yaml
  label: UGC Agent Messages API
  slug: ugcagent-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ugcagent/openapi/ugcagent-messages-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and legally able to enter into this agreement.
    type: individual
  minimum_age:
    text: You must be at least 18 years old and legally able to enter into this agreement.
    value: '18'
  restricted_uses:
  - summary: High-impact decisions
    text: use the Service to make decisions about employment, credit, housing, insurance, education admission, healthcare, or another high-impact field
  - summary: Children or sensitive characteristics
    text: seek or process information about children or highly sensitive personal characteristics
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may require verification before changing ownership, billing, or account access.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: UGC Agent
provenance_date: '2026-11-10'
provider_name: UGC Agent
provider_slug: ugcagent
slug: ugcagent-eligibility
source_date: '2026-11-10'
source_filename: ugcagent-eligibility.yml
source_heading: Eligibility
source_page: https://ugcagent.app/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: UGC Agent\naid: ugcagent\nurl: https://ugcagent.app/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and legally able to enter into this agreement.\nrestricted_uses:\n- summary: High-impact decisions\n  text: use the Service to make decisions about employment, credit, housing, insurance, education admission, healthcare,\n    or another high-impact field\n- summary: Children or sensitive characteristics\n  text: seek or process information about children or highly sensitive personal characteristics\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may require verification before changing ownership, billing, or account access.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and legally able to enter into this agreement.\n"
source_yaml_url: https://artifacts.apis.io/ugcagent/eligibility/ugcagent-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from UGC Agent's own page on 2026-11-10.
synthetic: false
tags:
- Company
- UGC
- Marketing
- Data
- Creators
---
