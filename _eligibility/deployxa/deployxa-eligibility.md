---
api_specs:
- filename: deployxa-deployments-api-openapi.yml
  format: yaml
  label: Deployxa Deployments API
  slug: deployxa-deployments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deployxa/openapi/deployxa-deployments-api-openapi.yml
- filename: deployxa-projects-api-openapi.yml
  format: yaml
  label: Deployxa Projects API
  slug: deployxa-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deployxa/openapi/deployxa-projects-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Service on behalf of a company or other organization, you confirm that you have authority to bind it, and “you” means that organization.
    type: business
  minimum_age:
    text: You must be at least 16 years old and provide accurate information when you register.
    value: '16'
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
name: Deployxa
provenance_date: '2026-11-09'
provider_name: Deployxa
provider_slug: deployxa
slug: deployxa-eligibility
source_date: '2026-11-09'
source_filename: deployxa-eligibility.yml
source_heading: Eligibility
source_page: https://deployxa.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Deployxa\naid: deployxa\nurl: https://deployxa.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Service on behalf of a company or other organization, you confirm that you have authority\n    to bind it, and “you” means that organization.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old and provide accurate information when you register.\n"
source_yaml_url: https://artifacts.apis.io/deployxa/eligibility/deployxa-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Deployxa's own page on 2026-11-09.
synthetic: false
tags:
- Platform-as-a-Service
- Cloud Deployment
- DevOps
- CI/CD
- containers-docker
- edge-hosting
- Managed Database
- AIOps
- Developer Tools
- A2A
---
