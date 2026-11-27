---
api_specs:
- filename: factory-automations-api-openapi.yml
  format: yaml
  label: Factory Automations API
  slug: factory-automations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/factory/openapi/factory-automations-api-openapi.yml
- filename: factory-computers-api-openapi.yml
  format: yaml
  label: Factory Computers API
  slug: factory-computers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/factory/openapi/factory-computers-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: an individual accepting this Agreement who plans to access or use the Service(s) in a personal capacity
    type: individual
  - text: the organization that the individual accepting this Agreement represents
    type: business
  minimum_age:
    text: AFFIRMS THAT IT IS AT LEAST 18 YEARS OF AGE (OR HAS REACHED THE AGE OF MAJORITY IN THE JURISDICTION WHERE CUSTOMER RESIDES)
    value: '18'
  restricted_uses:
  - summary: Competition with Factory
    text: Customer may not use or display the Service in competition with Factory, to develop competing products or services
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
name: Factory
provenance_date: '2026-11-09'
provider_name: Factory
provider_slug: factory
slug: factory-eligibility
source_date: '2026-11-09'
source_filename: factory-eligibility.yml
source_heading: Eligibility
source_page: https://factory.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Factory\naid: factory\nurl: https://factory.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: an individual accepting this Agreement who plans to access or use the Service(s) in a personal capacity\n- type: business\n  text: the organization that the individual accepting this Agreement represents\nrestricted_uses:\n- summary: Competition with Factory\n  text: Customer may not use or display the Service in competition with Factory, to develop competing products or\n    services\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: AFFIRMS THAT IT IS AT LEAST 18 YEARS OF AGE (OR HAS REACHED THE AGE OF MAJORITY IN THE JURISDICTION WHERE\n    CUSTOMER RESIDES)\n"
source_yaml_url: https://artifacts.apis.io/factory/eligibility/factory-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Factory's own page on 2026-11-09.
synthetic: false
tags:
- Manufacturing
- Software-as-a-Service
- Cloud
- Automation
- Supply Chain
- Company
---
