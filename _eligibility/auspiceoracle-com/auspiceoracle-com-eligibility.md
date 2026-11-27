---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 16 years old (or the age of digital consent where you live) to use the service.
    type: individual
  minimum_age:
    text: You must be at least 16 years old (or the age of digital consent where you live) to use the service.
    value: '16'
  restricted_uses:
  - summary: Not medical, legal, financial or investment advice
    text: Readings and conversations are not medical, psychological, legal, financial, or investment advice
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: 'Sign-in is passwordless: we email a sign-in link to the address you provide, valid for 3 days.'
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Auspice Oracle
provenance_date: '2026-11-09'
provider_name: Auspice Oracle
provider_slug: auspiceoracle-com
slug: auspiceoracle-com-eligibility
source_date: '2026-11-09'
source_filename: auspiceoracle-com-eligibility.yml
source_heading: Eligibility
source_page: https://auspiceoracle.com/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Auspice Oracle\naid: auspiceoracle-com\nurl: https://auspiceoracle.com/en/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 16 years old (or the age of digital consent where you live) to use the service.\nrestricted_uses:\n- summary: Not medical, legal, financial or investment advice\n  text: Readings and conversations are not medical, psychological, legal, financial, or investment advice\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: 'Sign-in is passwordless: we email a sign-in\
  \ link to the address you provide, valid for 3 days.'\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old (or the age of digital consent where you live) to use the service.\n"
source_yaml_url: https://artifacts.apis.io/auspiceoracle-com/eligibility/auspiceoracle-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Auspice Oracle's own page on 2026-11-09.
synthetic: false
tags:
- Astrology
- Chinese Philosophy
- BaZi
- Self-Reflection
- Company
---
