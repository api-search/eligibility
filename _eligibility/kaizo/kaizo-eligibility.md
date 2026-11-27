---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: a natural or legal person who has accepted the Terms
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or obscene data
    text: store prohibited material including any data that is obscene, threatening, libelous, or otherwise unlawful or tortuous
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
name: Kaizo
provenance_date: '2026-11-09'
provider_name: Kaizo
provider_slug: kaizo
slug: kaizo-eligibility
source_date: '2026-11-09'
source_filename: kaizo-eligibility.yml
source_heading: Eligibility
source_page: https://www.kaizo.com/legal/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kaizo\naid: kaizo\nurl: https://www.kaizo.com/legal/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: a natural or legal person who has accepted the Terms\nrestricted_uses:\n- summary: Unlawful or obscene data\n  text: store prohibited material including any data that is obscene, threatening, libelous, or otherwise unlawful\n    or tortuous\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/kaizo/eligibility/kaizo-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Kaizo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Quality Assurance
- Customer Service
- Contact Center
- Performance Management
- Artificial Intelligence
- Zendesk
- Salesforce
---
