---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: een ondernemer/onderneming of consument die gebruik maakt van onze website
    type: individual
  - text: een ondernemer/onderneming of consument die gebruik maakt van onze website
    type: business
  minimum_age:
    text: null
    value: null
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
name: Insify
provenance_date: '2026-11-09'
provider_name: Insify
provider_slug: insify
slug: insify-eligibility
source_date: '2026-11-09'
source_filename: insify-eligibility.yml
source_heading: Eligibility
source_page: https://www.insify.nl/voorwaarden/algemene-voorwaarden/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Insify\naid: insify\nurl: https://www.insify.nl/voorwaarden/algemene-voorwaarden/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: een ondernemer/onderneming of consument die gebruik maakt van onze website\n- type: business\n  text: een ondernemer/onderneming of consument die gebruik maakt van onze website\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/insify/eligibility/insify-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from Insify's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Insurance Tech
- Insurance
- Business Insurance
- Freelancers
- Self-Employed
- Small Business
- Netherlands
- Liability Insurance
- Disability Insurance
---
