---
api_specs:
- filename: contra-public-api-api-openapi.yml
  format: yaml
  label: Contra Public Api
  slug: contra-public-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contra/openapi/contra-public-api-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: an individual at least 18 years old or of the age of majority in your country and capable of forming binding contracts
    type: individual
  - text: You may use the Platform only if you are a legal entity
    type: business
  minimum_age:
    text: an individual over the age of 18 (or age of majority in your country)
    value: '18'
  restricted_uses:
  - summary: No personal or consumer use
    text: You may use the Platform for business purposes only and not for personal or consumer use.
  - summary: No physical goods
    text: The Platform is not intended for the sale of physical, non-digital products.
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
name: Contra
provenance_date: '2026-11-09'
provider_name: Contra
provider_slug: contra
slug: contra-eligibility
source_date: '2026-11-09'
source_filename: contra-eligibility.yml
source_heading: Eligibility
source_page: https://contra.com/policies/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Contra\naid: contra\nurl: https://contra.com/policies/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: an individual at least 18 years old or of the age of majority in your country and capable of forming binding\n    contracts\n- type: business\n  text: You may use the Platform only if you are a legal entity\nrestricted_uses:\n- summary: No personal or consumer use\n  text: You may use the Platform for business purposes only and not for personal or consumer use.\n- summary: No physical goods\n  text: The Platform\
  \ is not intended for the sale of physical, non-digital products.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: an individual over the age of 18 (or age of majority in your country)\n"
source_yaml_url: https://artifacts.apis.io/contra/eligibility/contra-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Contra's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Future Of Work
- Freelance Marketplace
- Talent
- Hiring
- Professional Network
- MCP
- Developer API
---
