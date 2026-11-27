---
api_specs:
- filename: consensus-app-openapi-generated.yml
  format: yaml
  label: Consensus API
  slug: consensus-app-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/consensus-app/openapi/_ae-authored/consensus-app-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: access to the Site from locations where such activity is illegal is prohibited
  minimum_age:
    text: You must be at least 13 years old to use the Services.
    value: '13'
  restricted_uses:
  - summary: No medical advice
    text: The Company does not provide medical advice or any service for which a medical license is required.
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
name: Consensus
provenance_date: '2026-11-09'
provider_name: Consensus
provider_slug: consensus-app
slug: consensus-app-eligibility
source_date: '2026-11-09'
source_filename: consensus-app-eligibility.yml
source_heading: Eligibility
source_page: https://consensus.app/home/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Consensus\naid: consensus-app\nurl: https://consensus.app/home/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: access to the Site from locations where such activity is illegal is prohibited\nentity_types: []\nrestricted_uses:\n- summary: No medical advice\n  text: The Company does not provide medical advice or any service for which a medical license is required.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/consensus-app/eligibility/consensus-app-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Consensus's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- EducationalApplication
---
