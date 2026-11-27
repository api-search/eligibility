---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into the Agreement on behalf of your customer, business or other legal entity, you represent that you have the authority to bind such entity and its affiliates to the Agreement
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Harassment or unfair competition
    text: not for the purposes of harassment, unfair competition, overreach, or other unlawful purposes
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
name: MarqVision
provenance_date: '2026-11-10'
provider_name: MarqVision
provider_slug: marqvision
slug: marqvision-eligibility
source_date: '2026-11-10'
source_filename: marqvision-eligibility.yml
source_heading: Eligibility
source_page: https://www.marqvision.com/marqai-tc
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MarqVision\naid: marqvision\nurl: https://www.marqvision.com/marqai-tc\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into the Agreement on behalf of your customer, business or other legal entity, you represent\n    that you have the authority to bind such entity and its affiliates to the Agreement\nrestricted_uses:\n- summary: Harassment or unfair competition\n  text: not for the purposes of harassment, unfair competition, overreach, or other unlawful purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/marqvision/eligibility/marqvision-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from MarqVision's own page on 2026-11-10.
synthetic: false
tags:
- Brand Protection
- Intellectual Property
- Anti-Counterfeiting
- Trademarks
- Content Protection
- E-Commerce
- Artificial Intelligence
- Trust and Safety
- Enforcement
- Company
---
