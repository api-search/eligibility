---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you certify to Iframely that you are legally authorized to form a binding contract for the use of Services between Iframely and you or legal entity you represent.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal or unauthorized purposes
    text: You may not use the Services for any illegal or unauthorized purpose.
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
name: Iframely
provenance_date: '2026-11-09'
provider_name: Iframely
provider_slug: iframely
slug: iframely-eligibility
source_date: '2026-11-09'
source_filename: iframely-eligibility.yml
source_heading: Eligibility
source_page: https://iframely.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Iframely\naid: iframely\nurl: https://iframely.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: you certify to Iframely that you are legally authorized to form a binding contract for the use of Services\n    between Iframely and you or legal entity you represent.\nrestricted_uses:\n- summary: Illegal or unauthorized purposes\n  text: You may not use the Services for any illegal or unauthorized purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/iframely/eligibility/iframely-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Iframely's own page on 2026-11-09.
synthetic: false
tags:
- Embed
- Media
- URLs
- Content
---
