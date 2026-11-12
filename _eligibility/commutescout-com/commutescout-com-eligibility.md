---
api_specs:
- filename: commutescout-com-tools-api-openapi.yml
  format: yaml
  label: CommuteScout Tools API
  slug: commutescout-com-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commutescout-com/openapi/commutescout-com-tools-api-openapi.yml
claim_count: 2
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
  - summary: Emergency decisions
    text: never rely on this service for evacuation or any emergency decision
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Watch-area accounts are an invite-gated trial. We can approve, limit, or revoke access at any time
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CommuteScout
provenance_date: '2026-11-09'
provider_name: CommuteScout
provider_slug: commutescout-com
slug: commutescout-com-eligibility
source_date: '2026-11-09'
source_filename: commutescout-com-eligibility.yml
source_heading: Eligibility
source_page: https://commutescout.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CommuteScout\naid: commutescout-com\nurl: https://commutescout.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Emergency decisions\n  text: never rely on this service for evacuation or any emergency decision\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Watch-area accounts are an invite-gated trial. We can approve, limit, or revoke access at any time\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/commutescout-com/eligibility/commutescout-com-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from CommuteScout's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Traffic
- Road Conditions
- Transportation
- Navigation
- Route Planning
- Maps
- MCP
- Open Source
---
