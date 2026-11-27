---
api_specs:
- filename: weverlabs-com-openapi.json
  format: json
  label: Wever Labs Agent API
  slug: wever-labs-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weverlabs-com/openapi/weverlabs-com-openapi.json
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: An organization’s representative accepts on its behalf.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Identify tests and operational work
    text: Identify tests as tests and operational work as operational work.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Protected tools check wallet ownership, credentials or a signed mandate for the action.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: weverlabs-com
provenance_date: '2026-11-10'
provider_name: weverlabs-com
provider_slug: weverlabs-com
slug: weverlabs-com-eligibility
source_date: '2026-11-10'
source_filename: weverlabs-com-eligibility.yml
source_heading: Eligibility
source_page: https://weverlabs.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: weverlabs-com\naid: weverlabs-com\nurl: https://weverlabs.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: An organization’s representative accepts on its behalf.\nrestricted_uses:\n- summary: Identify tests and operational work\n  text: Identify tests as tests and operational work as operational work.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Protected tools check wallet ownership, credentials or a signed mandate for the action.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/weverlabs-com/eligibility/weverlabs-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from weverlabs-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Payments
- Infrastructure
- Platform
---
