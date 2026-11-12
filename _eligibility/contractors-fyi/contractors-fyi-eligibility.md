---
claim_count: 1
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
  - summary: False requests
    text: Do not send false requests, try to break or overload the site, or copy large parts of it for another service.
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
name: contractors.fyi
provenance_date: '2026-11-09'
provider_name: contractors.fyi
provider_slug: contractors-fyi
slug: contractors-fyi-eligibility
source_date: '2026-11-09'
source_filename: contractors-fyi-eligibility.yml
source_heading: Eligibility
source_page: https://contractors.fyi/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: contractors.fyi\naid: contractors-fyi\nurl: https://contractors.fyi/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: False requests\n  text: Do not send false requests, try to break or overload the site, or copy large parts of it for another service.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/contractors-fyi/eligibility/contractors-fyi-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from contractors.fyi's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Contractors
- Home Improvement
- Building Permits
- Public Records
- Model Context Protocol
- Real Estate
---
