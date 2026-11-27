---
api_specs:
- filename: pnut-openapi-generated.yml
  format: yaml
  label: pnut.io API
  slug: pnut-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pnut/openapi/_ae-authored/pnut-openapi-generated.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Any payments made may require real names to be associated with payment information.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: pnut.io
provenance_date: '2026-11-10'
provider_name: pnut.io
provider_slug: pnut
slug: pnut-eligibility
source_date: '2026-11-10'
source_filename: pnut-eligibility.yml
source_heading: Eligibility
source_page: https://pnut.io/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: pnut.io\naid: pnut\nurl: https://pnut.io/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Any payments made may require real names to be associated with payment information.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/pnut/eligibility/pnut-eligibility.yml
stated_fields:
- verification
summary_line: 1 quoted statement, read from pnut.io's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Social
- API-First
- Community
- Sustainability
---
