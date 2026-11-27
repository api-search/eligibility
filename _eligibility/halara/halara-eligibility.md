---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you must be at least 16 years old, a "natural person" in your country of residence
    type: individual
  minimum_age:
    text: you must be at least 16 years old, a "natural person" in your country of residence
    value: '16'
  restricted_uses:
  - summary: Personal use only
    text: only for the purpose of shopping for personal items sold on the Sites or Apps and not for any commercial use or use on behalf of any third party
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
name: Halara
provenance_date: '2026-11-09'
provider_name: Halara
provider_slug: halara
slug: halara-eligibility
source_date: '2026-11-09'
source_filename: halara-eligibility.yml
source_heading: Eligibility
source_page: https://www.halara.com/pages/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Halara\naid: halara\nurl: https://www.halara.com/pages/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you must be at least 16 years old, a \"natural person\" in your country of residence\nrestricted_uses:\n- summary: Personal use only\n  text: only for the purpose of shopping for personal items sold on the Sites or Apps and not for any commercial\n    use or use on behalf of any third party\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ '16'\n  text: you must be at least 16 years old, a \"natural person\" in your country of residence\n"
source_yaml_url: https://artifacts.apis.io/halara/eligibility/halara-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Halara's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Retail
- E-Commerce
- Fashion
- Apparel
- Activewear
- Athleisure
- Direct to Consumer
- Shopify
---
