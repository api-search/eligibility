---
api_specs:
- filename: factline-dev-free-api-openapi.yml
  format: yaml
  label: factline-dev Free API
  slug: factline-dev-free-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/factline-dev/openapi/factline-dev-free-api-openapi.yml
- filename: factline-dev-paid-x402-api-openapi.yml
  format: yaml
  label: factline-dev Paid (x402) API
  slug: factline-dev-paid-x402-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/factline-dev/openapi/factline-dev-paid-x402-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Insolvency data limited use
    text: may only be used to inform yourself or other parties in business dealings about an insolvency.
  - summary: PEP results are not allegations
    text: Results are possible matches to support your own due diligence, not a finding about a person.
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
name: factline-dev
provenance_date: '2026-11-09'
provider_name: factline-dev
provider_slug: factline-dev
slug: factline-dev-eligibility
source_date: '2026-11-09'
source_filename: factline-dev-eligibility.yml
source_heading: Eligibility
source_page: https://factline.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: factline-dev\naid: factline-dev\nurl: https://factline.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Insolvency data limited use\n  text: may only be used to inform yourself or other parties in business dealings about an insolvency.\n- summary: PEP results are not allegations\n  text: Results are possible matches to support your own due diligence, not a finding about a person.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/factline-dev/eligibility/factline-dev-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from factline-dev's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Finance
- Compliance
- KYB
---
