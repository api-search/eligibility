---
api_specs:
- filename: fettle-sh-api-openapi.json
  format: json
  label: fettle.sh Api API
  slug: fettle-sh-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fettle-sh/openapi/_original/fettle-sh-api-openapi.json
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 16 years old to use the service.
    value: '16'
  restricted_uses:
  - summary: Monitor only owned or authorized targets
    text: Only monitor targets that you own or are explicitly authorized to probe.
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
name: fettle-sh
provenance_date: '2026-11-09'
provider_name: fettle-sh
provider_slug: fettle-sh
slug: fettle-sh-eligibility
source_date: '2026-11-09'
source_filename: fettle-sh-eligibility.yml
source_heading: Eligibility
source_page: https://fettle.sh/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: fettle-sh\naid: fettle-sh\nurl: https://fettle.sh/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Monitor only owned or authorized targets\n  text: Only monitor targets that you own or are explicitly authorized to probe.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old to use the service.\n"
source_yaml_url: https://artifacts.apis.io/fettle-sh/eligibility/fettle-sh-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from fettle-sh's own page on 2026-11-09.
synthetic: false
tags:
- Monitoring
- Uptime
- Developers
- AI Agents
---
