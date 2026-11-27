---
api_specs:
- filename: apidog-import-and-export-api-openapi.yml
  format: yaml
  label: Apidog Import And Export API
  slug: apidog-import-and-export-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apidog/openapi/apidog-import-and-export-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If registering or using the Service as an employee, contractor, or agent of an entity, you represent that you have full authority to bind such entity.
    type: business
  minimum_age:
    text: Apidog Services are available only to individuals who are 16 years or older, or the age of majority in your jurisdiction (18 in many territories, including the EEA/UK).
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
name: Apidog
provenance_date: '2026-11-09'
provider_name: Apidog
provider_slug: apidog
slug: apidog-eligibility
source_date: '2026-11-09'
source_filename: apidog-eligibility.yml
source_heading: Eligibility
source_page: https://legal.apidog.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Apidog\naid: apidog\nurl: https://legal.apidog.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If registering or using the Service as an employee, contractor, or agent of an entity, you represent that\n    you have full authority to bind such entity.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: Apidog Services are available only to individuals who are 16 years or older, or the age of majority in your\n    jurisdiction (18 in many territories,\
  \ including the EEA/UK).\n"
source_yaml_url: https://artifacts.apis.io/apidog/eligibility/apidog-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Apidog's own page on 2026-11-09.
synthetic: false
tags:
- AI Coding
- API Design
- API Lifecycle
- API Testing
- Collaboration
- Design-First
- Developer Tools
- Documentation
- MCP
- Mocking
- Platform
- Testing
---
