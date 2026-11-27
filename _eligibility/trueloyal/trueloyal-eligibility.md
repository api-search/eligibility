---
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
  - summary: Legally prohibited use
    text: You may not use the Services if you are legally prohibited from receiving or using the Services under the laws of the country in which you are resident or from which you access or use the Services.
  - summary: Regulated data uses
    text: You may not use the Services in a way that would violate local or industry-specific regulations (for example, the Children’s Online Privacy Protection Rule
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
name: TrueLoyal
provenance_date: '2026-11-10'
provider_name: TrueLoyal
provider_slug: trueloyal
slug: trueloyal-eligibility
source_date: '2026-11-10'
source_filename: trueloyal-eligibility.yml
source_heading: Eligibility
source_page: https://www.trueloyal.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TrueLoyal\naid: trueloyal\nurl: https://www.trueloyal.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Legally prohibited use\n  text: You may not use the Services if you are legally prohibited from receiving or using the Services under the\n    laws of the country in which you are resident or from which you access or use the Services.\n- summary: Regulated data uses\n  text: You may not use the Services in a way that would violate local or industry-specific regulations (for example,\n    the Children’s\
  \ Online Privacy Protection Rule\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/trueloyal/eligibility/trueloyal-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from TrueLoyal's own page on 2026-11-10.
synthetic: false
tags:
- Loyalty
- Platform
- Software-as-a-Service
- Retail
- Consumer Brand
- Company
---
