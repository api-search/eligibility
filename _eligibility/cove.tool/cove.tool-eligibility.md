---
api_specs:
- filename: cove.tool-authentication-token-api-openapi.yml
  format: yaml
  label: Cove.Tool Authentication Token API
  slug: cove.tool-authentication-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cove.tool/openapi/cove.tool-authentication-token-api-openapi.yml
- filename: cove.tool-daylight-analysis-api-openapi.yml
  format: yaml
  label: Cove.Tool Daylight Analysis API
  slug: cove.tool-daylight-analysis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cove.tool/openapi/cove.tool-daylight-analysis-api-openapi.yml
- filename: cove.tool-energy-codes-api-openapi.yml
  format: yaml
  label: Cove.Tool Energy Codes API
  slug: cove.tool-energy-codes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cove.tool/openapi/cove.tool-energy-codes-api-openapi.yml
- filename: cove.tool-profiles-api-openapi.yml
  format: yaml
  label: Cove.Tool Profiles API
  slug: cove.tool-profiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cove.tool/openapi/cove.tool-profiles-api-openapi.yml
- filename: cove.tool-project-geometry-api-openapi.yml
  format: yaml
  label: Cove.Tool Project Geometry API
  slug: cove.tool-project-geometry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cove.tool/openapi/cove.tool-project-geometry-api-openapi.yml
- filename: cove.tool-projects-api-openapi.yml
  format: yaml
  label: Cove.Tool Projects API
  slug: cove.tool-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cove.tool/openapi/cove.tool-projects-api-openapi.yml
- filename: cove.tool-user-api-openapi.yml
  format: yaml
  label: Cove.Tool User API
  slug: cove.tool-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cove.tool/openapi/cove.tool-user-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: not all Services, Software or features thereof may be available in your country.
  entity_types:
  - text: User Accounts are restricted to those persons 18 years of age or older at the time of registration.
    type: individual
  - text: A User Account may be created for you by an administrator, such as your employer.
    type: business
  minimum_age:
    text: User Accounts are restricted to those persons 18 years of age or older at the time of registration.
    value: '18'
  restricted_uses:
  - summary: Prisons design
    text: use cove to design prisons
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Each User Account must have the associated e-mail address verified within seven (7) days of the User Account’s creation to remain active.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cove.Tool
provenance_date: '2026-11-09'
provider_name: Cove.Tool
provider_slug: cove.tool
slug: cove.tool-eligibility
source_date: '2026-11-09'
source_filename: cove.tool-eligibility.yml
source_heading: Eligibility
source_page: https://cove.inc/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cove.Tool\naid: cove.tool\nurl: https://cove.inc/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: not all Services, Software or features thereof may be available in your country.\nentity_types:\n- type: individual\n  text: User Accounts are restricted to those persons 18 years of age or older at the time of registration.\n- type: business\n  text: A User Account may be created for you by an administrator, such as your employer.\nrestricted_uses:\n- summary: Prisons design\n  text: use cove to design prisons\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: Each User Account must have the associated e-mail address verified within seven (7) days of the User Account’s\n    creation to remain active.\nminimum_age:\n  value: '18'\n  text: User Accounts are restricted to those persons 18 years of age or older at the time of registration.\n"
source_yaml_url: https://artifacts.apis.io/cove.tool/eligibility/cove.tool-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Cove.Tool's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Building Performance
- Energy Modeling
- Daylight Analysis
- Sustainability
- Architecture
- AEC
- Simulation
- Embodied Carbon
- Building Design
---
