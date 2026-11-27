---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You are at least 13 years of age and have the authority to enter into this Agreement
    type: individual
  - text: to the extent an individual is accepting this Agreement on behalf of an entity, such individual has the right and authority to agree to all of the terms set forth herein on behalf of such entity
    type: business
  minimum_age:
    text: You are at least 13 years of age
    value: '13'
  restricted_uses:
  - summary: Gambling and lottery prohibited
    text: any form of lottery or gambling
  - summary: Unlawful or harassing uses prohibited
    text: is unlawful, threatening, abusive, harassing, defamatory, libelous, deceptive, fraudulent
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
name: Belly
provenance_date: '2026-11-09'
provider_name: Belly
provider_slug: belly
slug: belly-eligibility
source_date: '2026-11-09'
source_filename: belly-eligibility.yml
source_heading: Eligibility
source_page: https://www.bellycard.com/terms-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Belly\naid: belly\nurl: https://www.bellycard.com/terms-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You are at least 13 years of age and have the authority to enter into this Agreement\n- type: business\n  text: to the extent an individual is accepting this Agreement on behalf of an entity, such individual has the\n    right and authority to agree to all of the terms set forth herein on behalf of such entity\nrestricted_uses:\n- summary: Gambling and lottery prohibited\n  text: any form of lottery or\
  \ gambling\n- summary: Unlawful or harassing uses prohibited\n  text: is unlawful, threatening, abusive, harassing, defamatory, libelous, deceptive, fraudulent\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You are at least 13 years of age\n"
source_yaml_url: https://artifacts.apis.io/belly/eligibility/belly-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Belly's own page on 2026-11-09.
synthetic: false
tags:
- Loyalty
- Marketing
- Small Business
- Retail
- Software-as-a-Service
- Company
---
