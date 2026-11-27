---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Service is operated in the United States, and is primarily intended for users located in the U.S.
  entity_types:
  - text: Individuals must be a certain age (and at least the age of majority in their state of residence) in order to create an account or use the Service.
    type: individual
  minimum_age:
    text: Individuals must be a certain age (and at least the age of majority in their state of residence) in order to create an account or use the Service.
    value: age of majority in state of residence
  restricted_uses:
  - summary: Federal law compliance
    text: Our Service is not intended to assist you in violating federal law.
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
name: PharmaCann
provenance_date: '2026-11-10'
provider_name: PharmaCann
provider_slug: pharmacann
slug: pharmacann-eligibility
source_date: '2026-11-10'
source_filename: pharmacann-eligibility.yml
source_heading: Eligibility
source_page: https://www.pharmacann.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PharmaCann\naid: pharmacann\nurl: https://www.pharmacann.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Service is operated in the United States, and is primarily intended for users located in the U.S.\nentity_types:\n- type: individual\n  text: Individuals must be a certain age (and at least the age of majority in their state of residence) in order\n    to create an account or use the Service.\nrestricted_uses:\n- summary: Federal law compliance\n  text: Our Service is not intended to assist you in violating federal law.\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority in state of residence\n  text: Individuals must be a certain age (and at least the age of majority in their state of residence) in order\n    to create an account or use the Service.\n"
source_yaml_url: https://artifacts.apis.io/pharmacann/eligibility/pharmacann-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from PharmaCann's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cannabis
- Retail
- Agriculture
- Consumer Goods
- Manufacturing
- Health
- Dispensary
---
