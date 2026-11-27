---
api_specs:
- filename: cflow-requests-api-openapi.yml
  format: yaml
  label: Cflow Requests API
  slug: cflow-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cflow/openapi/cflow-requests-api-openapi.yml
- filename: cflow-users-api-openapi.yml
  format: yaml
  label: Cflow Users API
  slug: cflow-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cflow/openapi/cflow-users-api-openapi.yml
- filename: cflow-workflows-api-openapi.yml
  format: yaml
  label: Cflow Workflows API
  slug: cflow-workflows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cflow/openapi/cflow-workflows-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may use the Services for business use or for internal business purposes in the organization that you represent.
    type: business
  minimum_age:
    text: You must be of legal age to enter into a binding agreement in order to accept the Terms.
    value: legal age
  restricted_uses:
  - summary: Spam and illegal activity
    text: We reserve the right to terminate your access to the Services if there are reasonable grounds to believe that you have used the Services for any illegal or unauthorized activity.
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
name: Cflow
provenance_date: '2026-11-09'
provider_name: Cflow
provider_slug: cflow
slug: cflow-eligibility
source_date: '2026-11-09'
source_filename: cflow-eligibility.yml
source_heading: Eligibility
source_page: https://www.cflowapps.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cflow\naid: cflow\nurl: https://www.cflowapps.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: You may use the Services for business use or for internal business purposes in the organization that you\n    represent.\nrestricted_uses:\n- summary: Spam and illegal activity\n  text: We reserve the right to terminate your access to the Services if there are reasonable grounds to believe\n    that you have used the Services for any illegal or unauthorized activity.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: legal age\n  text: You must be of legal age to enter into a binding agreement in order to accept the Terms.\n"
source_yaml_url: https://artifacts.apis.io/cflow/eligibility/cflow-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Cflow's own page on 2026-11-09.
synthetic: false
tags:
- Automation
- Business Process Automation
- Integration
- No-Code
- Platform
- Protocol
- Rules
- Workflows
---
