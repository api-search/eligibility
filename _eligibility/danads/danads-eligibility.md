---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'Advertiser: Any individual, company, agency, or other entity that creates an account on the Platform and uses it to purchase, fund, or manage advertising campaigns'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Creative content must comply with law and Publisher guidelines
    text: Advertiser submits creative content that violates applicable laws, regulations, or Publisher guidelines.
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
name: DanAds
provenance_date: '2026-11-09'
provider_name: DanAds
provider_slug: danads
slug: danads-eligibility
source_date: '2026-11-09'
source_filename: danads-eligibility.yml
source_heading: Eligibility
source_page: https://danads.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DanAds\naid: danads\nurl: https://danads.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 'Advertiser: Any individual, company, agency, or other entity that creates an account on the Platform and\n    uses it to purchase, fund, or manage advertising campaigns'\nrestricted_uses:\n- summary: Creative content must comply with law and Publisher guidelines\n  text: Advertiser submits creative content that violates applicable laws, regulations, or Publisher guidelines.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/danads/eligibility/danads-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from DanAds's own page on 2026-11-09.
synthetic: false
tags:
- AdTech
- Publisher Tools
- Advertiser Tools
- Ad Operations
- Self‑Serve Advertising
---
