---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 13 years old (16 in the EU/UK) to use the Service.
    type: individual
  minimum_age:
    text: You must be at least 13 years old (16 in the EU/UK) to use the Service.
    value: '13'
  restricted_uses:
  - summary: Prohibited content
    text: 'You may not publish content that: Infringes someone else''s copyright, trademark, or other rights. Is illegal, defamatory, hateful, or harassing.'
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
name: Boonful
provenance_date: '2026-11-09'
provider_name: Boonful
provider_slug: boonful-io
slug: boonful-io-eligibility
source_date: '2026-11-09'
source_filename: boonful-io-eligibility.yml
source_heading: Eligibility
source_page: https://boonful.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Boonful\naid: boonful-io\nurl: https://boonful.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 13 years old (16 in the EU/UK) to use the Service.\nrestricted_uses:\n- summary: Prohibited content\n  text: 'You may not publish content that: Infringes someone else''s copyright, trademark, or other rights. Is illegal,\n    defamatory, hateful, or harassing.'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years\
  \ old (16 in the EU/UK) to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/boonful-io/eligibility/boonful-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Boonful's own page on 2026-11-09.
synthetic: false
tags:
- Publishing
- Software-as-a-Service
- E-Commerce
- Content Creation
- No-Code
---
