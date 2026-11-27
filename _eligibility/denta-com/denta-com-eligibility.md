---
api_specs:
- filename: denta-com-openapi-generated.yml
  format: yaml
  label: Denta API
  slug: denta-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/denta-com/openapi/_ae-authored/denta-com-openapi-generated.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Your company chooses the spending limits, funds employee transactions, and decides who may use the service.
    type: business
  minimum_age:
    text: null
    value: null
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
name: Denta
provenance_date: '2026-11-09'
provider_name: Denta
provider_slug: denta-com
slug: denta-com-eligibility
source_date: '2026-11-09'
source_filename: denta-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.denta.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Denta\naid: denta-com\nurl: https://www.denta.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Your company chooses the spending limits, funds employee transactions, and decides who may use the service.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/denta-com/eligibility/denta-com-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Denta's own page on 2026-11-09.
synthetic: false
tags:
- Dental
- Benefits
- Software-as-a-Service
- Healthcare
- Employer
---
