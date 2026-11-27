---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be 13 or older to use juli and create an account with us.
    type: individual
  minimum_age:
    text: You must be 13 or older to use juli and create an account with us.
    value: '13'
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
name: Juli
provenance_date: '2026-11-09'
provider_name: Juli
provider_slug: juli
slug: juli-eligibility
source_date: '2026-11-09'
source_filename: juli-eligibility.yml
source_heading: Eligibility
source_page: https://www.juli.co/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Juli\naid: juli\nurl: https://www.juli.co/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be 13 or older to use juli and create an account with us.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be 13 or older to use juli and create an account with us.\n"
source_yaml_url: https://artifacts.apis.io/juli/eligibility/juli-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Juli's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Digital Health
- Chronic Conditions
- Mental Health
- Asthma
- Depression
- Bipolar Disorder
- Migraine
- mHealth
- Wearables
- Artificial Intelligence
- Health Tech
---
