---
api_specs:
- filename: qrx-codes-api-openapi.yml
  format: yaml
  label: QRX Codes API
  slug: qrx-codes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qrx/openapi/qrx-codes-api-openapi.yml
- filename: qrx-qrx-api-api-openapi.yml
  format: yaml
  label: QRX QRX API
  slug: qrx-qrx-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qrx/openapi/qrx-qrx-api-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: By accessing the Services, You confirm that You are at least 13 years old and meet the minimum age of digital consent in Your country.
    value: '13'
  restricted_uses:
  - summary: Acceptable use guidelines
    text: By using QRX, you agree to create and display content that adheres to the following guidelines
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
name: QRX
provenance_date: '2026-11-10'
provider_name: QRX
provider_slug: qrx
slug: qrx-eligibility
source_date: '2026-11-10'
source_filename: qrx-eligibility.yml
source_heading: Eligibility
source_page: https://qrx.codes/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: QRX\naid: qrx\nurl: https://qrx.codes/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Acceptable use guidelines\n  text: By using QRX, you agree to create and display content that adheres to the following guidelines\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: By accessing the Services, You confirm that You are at least 13 years old and meet the minimum age of digital\n    consent in Your country.\n"
source_yaml_url: https://artifacts.apis.io/qrx/eligibility/qrx-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from QRX's own page on 2026-11-10.
synthetic: false
tags:
- Company
- QR Codes
- Artificial Intelligence
- Art
---
