---
api_specs:
- filename: sofy-applications-api-openapi.yml
  format: yaml
  label: SOFY Applications API
  slug: sofy-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sofy/openapi/sofy-applications-api-openapi.yml
- filename: sofy-scheduled-runs-api-openapi.yml
  format: yaml
  label: SOFY Scheduled Runs API
  slug: sofy-scheduled-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sofy/openapi/sofy-scheduled-runs-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'Customer represents and warrants that it and all Authorized Users are not: (i) a resident of any country subject to a United States embargo or other similar United States export restrictions'
  entity_types:
  - text: IF ENTERING INTO THE AGREEMENT FOR AN ORGANIZATION, THAT CUSTOMER HAS THE LEGAL AUTHORITY TO BIND THAT ORGANIZATION
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Building a competitive product
    text: using or accessing Services to build a competitive product or service
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
name: SOFY
provenance_date: '2026-11-10'
provider_name: SOFY
provider_slug: sofy
slug: sofy-eligibility
source_date: '2026-11-10'
source_filename: sofy-eligibility.yml
source_heading: Eligibility
source_page: https://sofy.ai/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SOFY\naid: sofy\nurl: https://sofy.ai/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 'Customer represents and warrants that it and all Authorized Users are not: (i) a resident of any country\n    subject to a United States embargo or other similar United States export restrictions'\nentity_types:\n- type: business\n  text: IF ENTERING INTO THE AGREEMENT FOR AN ORGANIZATION, THAT CUSTOMER HAS THE LEGAL AUTHORITY TO BIND THAT ORGANIZATION\nrestricted_uses:\n- summary: Building a competitive product\n  text: using or accessing Services to build a competitive product\
  \ or service\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sofy/eligibility/sofy-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from SOFY's own page on 2026-11-10.
synthetic: false
tags:
- Company
- AI Testing
- Test Automation
- Mobile Testing
- QA
- No-Code
- Continuous Testing
- DevOps
---
