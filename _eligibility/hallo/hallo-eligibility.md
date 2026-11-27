---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may access and use the Services for your personal use
    type: individual
  - text: 'When using or opening an account with Hallo on behalf of a company, entity, or organization (collectively, “Subscribing Organization”), you represent and warrant that you: (i) are an authorized representative of that Subscribing Organization'
    type: business
  minimum_age:
    text: The Services are directed to persons 18 years of age or older or of children 13 years of age or older who have a parent’s, legal guardian’s, or other caregiver’s consent.
    value: '13'
  restricted_uses:
  - summary: Solely automated decisions
    text: The Services are not intended to be used as a solely automated decision-making system where such use is restricted or prohibited by applicable law
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
name: Hallo
provenance_date: '2026-11-09'
provider_name: Hallo
provider_slug: hallo
slug: hallo-eligibility
source_date: '2026-11-09'
source_filename: hallo-eligibility.yml
source_heading: Eligibility
source_page: https://hallo.ai/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hallo\naid: hallo\nurl: https://hallo.ai/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may access and use the Services for your personal use\n- type: business\n  text: 'When using or opening an account with Hallo on behalf of a company, entity, or organization (collectively,\n    “Subscribing Organization”), you represent and warrant that you: (i) are an authorized representative of that\n    Subscribing Organization'\nrestricted_uses:\n- summary: Solely automated decisions\n  text: The Services are not intended\
  \ to be used as a solely automated decision-making system where such use is\n    restricted or prohibited by applicable law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Services are directed to persons 18 years of age or older or of children 13 years of age or older who\n    have a parent’s, legal guardian’s, or other caregiver’s consent.\n"
source_yaml_url: https://artifacts.apis.io/hallo/eligibility/hallo-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Hallo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Language Assessment
- Language Learning
- Artificial Intelligence
- Recruiting
- Human Resources
- Education
- Speech Recognition
---
