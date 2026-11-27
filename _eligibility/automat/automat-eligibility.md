---
api_specs:
- filename: automat-extract-api-openapi.yml
  format: yaml
  label: Automat Extract API
  slug: automat-extract-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/automat/openapi/automat-extract-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you have the authority to bind Customer to the terms and conditions of this Agreement
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export control restrictions
    text: used for any purposes prohibited by the Export Laws, including, but not limited to, nuclear, chemical, or biological weapons proliferation, missile systems or technology
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
name: Automat
provenance_date: '2026-11-09'
provider_name: Automat
provider_slug: automat
slug: automat-eligibility
source_date: '2026-11-09'
source_filename: automat-eligibility.yml
source_heading: Eligibility
source_page: https://runautomat.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Automat\naid: automat\nurl: https://runautomat.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: you have the authority to bind Customer to the terms and conditions of this Agreement\nrestricted_uses:\n- summary: Export control restrictions\n  text: used for any purposes prohibited by the Export Laws, including, but not limited to, nuclear, chemical, or\n    biological weapons proliferation, missile systems or technology\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/automat/eligibility/automat-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Automat's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Enterprise Saas
- Automation
- RPA
- Document Extraction
- Intelligent Document Processing
- iPaaS
- AI Agents
- Computer Use
- Document Processing
---
