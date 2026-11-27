---
api_specs:
- filename: trato-contracts-api-openapi.yml
  format: yaml
  label: Trato Contracts API
  slug: trato-contracts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trato/openapi/trato-contracts-api-openapi.yml
- filename: trato-custom-properties-api-openapi.yml
  format: yaml
  label: Trato Custom Properties API
  slug: trato-custom-properties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trato/openapi/trato-custom-properties-api-openapi.yml
- filename: trato-participants-api-openapi.yml
  format: yaml
  label: Trato Participants API
  slug: trato-participants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trato/openapi/trato-participants-api-openapi.yml
- filename: trato-spectators-api-openapi.yml
  format: yaml
  label: Trato Spectators API
  slug: trato-spectators-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trato/openapi/trato-spectators-api-openapi.yml
- filename: trato-templates-api-openapi.yml
  format: yaml
  label: Trato Templates API
  slug: trato-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trato/openapi/trato-templates-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are a business or acting for professional purposes, you and TRATO (TRATO Legaltech, S.L.) irrevocably agree to submit to the exclusive jurisdiction of the courts of the city of Madrid, Spain.
    type: business
  - text: If you are a consumer (a natural person acting for purposes outside their trade, business, craft or profession) resident in the European Economic Area (EEA), you have the following right
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal or fraudulent use
    text: Use the Services for illegal, fraudulent or unauthorized purposes.
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
name: Trato
provenance_date: '2026-11-10'
provider_name: Trato
provider_slug: trato
slug: trato-eligibility
source_date: '2026-11-10'
source_filename: trato-eligibility.yml
source_heading: Eligibility
source_page: https://trato.io/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Trato\naid: trato\nurl: https://trato.io/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are a business or acting for professional purposes, you and TRATO (TRATO Legaltech, S.L.) irrevocably\n    agree to submit to the exclusive jurisdiction of the courts of the city of Madrid, Spain.\n- type: individual\n  text: If you are a consumer (a natural person acting for purposes outside their trade, business, craft or profession)\n    resident in the European Economic Area (EEA), you have the following right\nrestricted_uses:\n\
  - summary: Illegal or fraudulent use\n  text: Use the Services for illegal, fraudulent or unauthorized purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/trato/eligibility/trato-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Trato's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Contract Management
- Contract Lifecycle Management
- E-Signature
- Legal Tech
- Document Management
- Workflow Automation
- Legal
---
