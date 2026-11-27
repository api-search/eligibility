---
api_specs:
- filename: eutexa-com-openapi-generated.yml
  format: yaml
  label: Eutexa API
  slug: eutexa-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eutexa-com/openapi/_ae-authored/eutexa-com-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: One person or legal entity may maintain no more than one free account.
    type: individual
  minimum_age:
    text: You must be at least 16 years old to create an account.
    value: '16'
  restricted_uses:
  - summary: Calling features compliance
    text: You are solely responsible for complying with all laws applicable to that call in every jurisdiction it touches, including the jurisdiction of the recipient.
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
name: Eutexa
provenance_date: '2026-11-09'
provider_name: Eutexa
provider_slug: eutexa-com
slug: eutexa-com-eligibility
source_date: '2026-11-09'
source_filename: eutexa-com-eligibility.yml
source_heading: Eligibility
source_page: https://eutexa.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Eutexa\naid: eutexa-com\nurl: https://eutexa.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: One person or legal entity may maintain no more than one free account.\nrestricted_uses:\n- summary: Calling features compliance\n  text: You are solely responsible for complying with all laws applicable to that call in every jurisdiction it\n    touches, including the jurisdiction of the recipient.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at\
  \ least 16 years old to create an account.\n"
source_yaml_url: https://artifacts.apis.io/eutexa-com/eligibility/eutexa-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Eutexa's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- CRM
- Software-as-a-Service
- B2B
- Automation
---
