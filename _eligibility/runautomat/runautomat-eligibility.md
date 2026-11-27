---
api_specs:
- filename: runautomat-extract-api-openapi.yml
  format: yaml
  label: Runautomat Extract API
  slug: runautomat-extract-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/runautomat/openapi/runautomat-extract-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the company or entity on whose behalf you entered this Agreement (“you” or “Customer”)
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export control and sanctions
    text: Customer affirms that it is not named on, owned by, or acting on behalf of any U.S. government denied-party list
  - summary: Weapons proliferation and prohibited uses
    text: used for any purposes prohibited by the Export Laws, including, but not limited to, nuclear, chemical, or biological weapons proliferation
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
name: Runautomat
provenance_date: '2026-11-10'
provider_name: Runautomat
provider_slug: runautomat
slug: runautomat-eligibility
source_date: '2026-11-10'
source_filename: runautomat-eligibility.yml
source_heading: Eligibility
source_page: https://runautomat.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Runautomat\naid: runautomat\nurl: https://runautomat.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the company or entity on whose behalf you entered this Agreement (“you” or “Customer”)\nrestricted_uses:\n- summary: Export control and sanctions\n  text: Customer affirms that it is not named on, owned by, or acting on behalf of any U.S. government denied-party\n    list\n- summary: Weapons proliferation and prohibited uses\n  text: used for any purposes prohibited by the Export Laws, including, but not limited to,\
  \ nuclear, chemical, or\n    biological weapons proliferation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/runautomat/eligibility/runautomat-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Runautomat's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Automation
- RPA
- Document Processing
- Artificial Intelligence
- Machine Learning
- Data Extraction
- iPaaS
- Agents
---
