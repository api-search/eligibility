---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Materials, services and information intended for users of the Site are not for use by children under 13 years of age.
    value: '13'
  restricted_uses:
  - summary: Competing product development
    text: You agree not to use any information or knowledge gained from using our software to develop, operate, or assist in the development or operation of a competing product or service.
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
name: Arcana
provenance_date: '2026-11-09'
provider_name: Arcana
provider_slug: arcana
slug: arcana-eligibility
source_date: '2026-11-09'
source_filename: arcana-eligibility.yml
source_heading: Eligibility
source_page: https://www.arcana.io/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Arcana\naid: arcana\nurl: https://www.arcana.io/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Competing product development\n  text: You agree not to use any information or knowledge gained from using our software to develop, operate, or\n    assist in the development or operation of a competing product or service.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Materials, services and information intended for users of the Site are not for\
  \ use by children under 13\n    years of age.\n"
source_yaml_url: https://artifacts.apis.io/arcana/eligibility/arcana-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Arcana's own page on 2026-11-09.
synthetic: false
tags:
- Fintech
- Portfolio Management
- Hedge Funds
- Asset Management
- Analytics
---
