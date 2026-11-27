---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service/veratrak.com is only intended for Users that do not qualify as Consumers, such as Business Users.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or infringing use
    text: Users are solely responsible for making sure that their use of veratrak.com and/or the Service violates no applicable law, regulations or third-party rights.
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
name: Veratrak
provenance_date: '2026-11-10'
provider_name: Veratrak
provider_slug: veratrak
slug: veratrak-eligibility
source_date: '2026-11-10'
source_filename: veratrak-eligibility.yml
source_heading: Eligibility
source_page: https://www.veratrak.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Veratrak\naid: veratrak\nurl: https://www.veratrak.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Service/veratrak.com is only intended for Users that do not qualify as Consumers, such as Business Users.\nrestricted_uses:\n- summary: Unlawful or infringing use\n  text: Users are solely responsible for making sure that their use of veratrak.com and/or the Service violates\n    no applicable law, regulations or third-party rights.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/veratrak/eligibility/veratrak-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Veratrak's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Pharmaceuticals
- Life Sciences
- Supply Chain
- Supply Chain Visibility
- Logistics
- Data Integration
- EDI
- Compliance
---
