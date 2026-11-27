---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: The Site and its data relate to UK addresses only.
  entity_types:
  - text: The Site is intended for UK residents aged 18 or over who are looking for residential broadband, TV and phone deals.
    type: individual
  minimum_age:
    text: UK residents aged 18 or over
    value: '18'
  restricted_uses:
  - summary: No commercial service built on AI/MCP data
    text: You must not use them, or any data they return, to build or run a commercial service.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: By using it, you confirm that you meet these criteria.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: findbroadbanddeals-com
provenance_date: '2026-11-09'
provider_name: findbroadbanddeals-com
provider_slug: findbroadbanddeals-com
slug: findbroadbanddeals-com-eligibility
source_date: '2026-11-09'
source_filename: findbroadbanddeals-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.findbroadbanddeals.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: findbroadbanddeals-com\naid: findbroadbanddeals-com\nurl: https://www.findbroadbanddeals.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: The Site and its data relate to UK addresses only.\nentity_types:\n- type: individual\n  text: The Site is intended for UK residents aged 18 or over who are looking for residential broadband, TV and\n    phone deals.\nrestricted_uses:\n- summary: No commercial service built on AI/MCP data\n  text: You must not use them, or any data they return, to build or run a commercial service.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: By using it, you confirm that you meet these criteria.\nminimum_age:\n  value: '18'\n  text: UK residents aged 18 or over\n"
source_yaml_url: https://artifacts.apis.io/findbroadbanddeals-com/eligibility/findbroadbanddeals-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from findbroadbanddeals-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Broadband
- United Kingdom
- Comparison
- Consumer
---
