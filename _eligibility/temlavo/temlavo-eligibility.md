---
api_specs:
- filename: temlavo-documents-api-openapi.yml
  format: yaml
  label: Temlavo Documents API
  slug: temlavo-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/temlavo/openapi/temlavo-documents-api-openapi.yml
- filename: temlavo-usage-api-openapi.yml
  format: yaml
  label: Temlavo Usage API
  slug: temlavo-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/temlavo/openapi/temlavo-usage-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Temlavo is intended for business and professional use, not personal or household consumer use.
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
name: Temlavo
provenance_date: '2026-11-10'
provider_name: Temlavo
provider_slug: temlavo
slug: temlavo-eligibility
source_date: '2026-11-10'
source_filename: temlavo-eligibility.yml
source_heading: Eligibility
source_page: https://temlavo.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Temlavo\naid: temlavo\nurl: https://temlavo.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Temlavo is intended for business and professional use, not personal or household consumer use.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/temlavo/eligibility/temlavo-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Temlavo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Invoices
- Extraction
- Accounting
---
