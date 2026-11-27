---
api_specs:
- filename: qa-wolf-ci-api-openapi.yml
  format: yaml
  label: QA Wolf CI API
  slug: qa-wolf-ci-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qa-wolf/openapi/qa-wolf-ci-api-openapi.yml
- filename: qa-wolf-webhooks-api-openapi.yml
  format: yaml
  label: QA Wolf Webhooks API
  slug: qa-wolf-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qa-wolf/openapi/qa-wolf-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Provider is a software testing firm that provides services to technology companies
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export-control and prohibited weapons uses
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
name: QA Wolf
provenance_date: '2026-11-10'
provider_name: QA Wolf
provider_slug: qa-wolf
slug: qa-wolf-eligibility
source_date: '2026-11-10'
source_filename: qa-wolf-eligibility.yml
source_heading: Eligibility
source_page: https://www.qawolf.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: QA Wolf\naid: qa-wolf\nurl: https://www.qawolf.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Provider is a software testing firm that provides services to technology companies\nrestricted_uses:\n- summary: Export-control and prohibited weapons uses\n  text: used for any purposes prohibited by the Export Laws, including, but not limited to, nuclear, chemical, or\n    biological weapons proliferation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/qa-wolf/eligibility/qa-wolf-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from QA Wolf's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Developer Tools
- Testing
- Test Automation
- QA
- CI/CD
- Playwright
---
