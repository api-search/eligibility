---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be of legal age in your jurisdiction and legally permitted to use a service of this kind.
    type: individual
  minimum_age:
    text: You must be of legal age in your jurisdiction and legally permitted to use a service of this kind.
    value: null
  restricted_uses:
  - summary: Unlawful use
    text: Do not use the service where doing so would be unlawful.
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
name: f1ow
provenance_date: '2026-11-09'
provider_name: f1ow
provider_slug: f1ow-com
slug: f1ow-com-eligibility
source_date: '2026-11-09'
source_filename: f1ow-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.f1ow.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: f1ow\naid: f1ow-com\nurl: https://www.f1ow.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be of legal age in your jurisdiction and legally permitted to use a service of this kind.\nrestricted_uses:\n- summary: Unlawful use\n  text: Do not use the service where doing so would be unlawful.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You must be of legal age in your jurisdiction and legally permitted to use a service of this kind.\n"
source_yaml_url: https://artifacts.apis.io/f1ow-com/eligibility/f1ow-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from f1ow's own page on 2026-11-09.
synthetic: false
tags:
- Cryptocurrency
- Market Data
- Finance
- MCP
---
