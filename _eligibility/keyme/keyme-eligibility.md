---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that you are at least 18 years of age.
    type: individual
  minimum_age:
    text: You represent and warrant that you are at least 18 years of age. If you are under age 18, you may not, under any circumstances or for any reason, use the Services.
    value: '18'
  restricted_uses:
  - summary: Services only for own use
    text: the Services are offered only for your use, and not for the use or benefit of any third party.
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
name: KeyMe
provenance_date: '2026-11-09'
provider_name: KeyMe
provider_slug: keyme
slug: keyme-eligibility
source_date: '2026-11-09'
source_filename: keyme-eligibility.yml
source_heading: Eligibility
source_page: https://key.me/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: KeyMe\naid: keyme\nurl: https://key.me/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant that you are at least 18 years of age.\nrestricted_uses:\n- summary: Services only for own use\n  text: the Services are offered only for your use, and not for the use or benefit of any third party.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent and warrant that you are at least 18 years of age. If you are under age 18, you may not,\
  \ under\n    any circumstances or for any reason, use the Services.\n"
source_yaml_url: https://artifacts.apis.io/keyme/eligibility/keyme-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from KeyMe's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Locksmith
- Key Duplication
- Kiosk
- Security
- Access Control
- Retail
- Consumer Services
---
