---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We do not warrant that the content of this Platform complies with the laws of any country outside of Australia.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or harmful use
    text: You must use this Platform only for lawful purposes and for the purposes explicitly communicated to you.
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
name: Bupa
provenance_date: '2026-11-09'
provider_name: Bupa
provider_slug: bupa
slug: bupa-eligibility
source_date: '2026-11-09'
source_filename: bupa-eligibility.yml
source_heading: Eligibility
source_page: https://www.bupa.com.au/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bupa\naid: bupa\nurl: https://www.bupa.com.au/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We do not warrant that the content of this Platform complies with the laws of any country outside of Australia.\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or harmful use\n  text: You must use this Platform only for lawful purposes and for the purposes explicitly communicated to you.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bupa/eligibility/bupa-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Bupa's own page on 2026-11-09.
synthetic: false
tags:
- Insurance
- United Kingdom
- Health Insurance
- Life and Health
- Carrier
- Healthcare
- Aged Care
- Claims
- Policy Administration
---
