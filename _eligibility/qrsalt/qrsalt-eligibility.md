---
api_specs:
- filename: qrsalt-barcode-api-openapi.yml
  format: yaml
  label: QRSalt Barcode API
  slug: qrsalt-barcode-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qrsalt/openapi/qrsalt-barcode-api-openapi.yml
- filename: qrsalt-codes-api-openapi.yml
  format: yaml
  label: QRSalt Codes API
  slug: qrsalt-codes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qrsalt/openapi/qrsalt-codes-api-openapi.yml
- filename: qrsalt-domains-api-openapi.yml
  format: yaml
  label: QRSalt Domains API
  slug: qrsalt-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qrsalt/openapi/qrsalt-domains-api-openapi.yml
- filename: qrsalt-forms-api-openapi.yml
  format: yaml
  label: QRSalt Forms API
  slug: qrsalt-forms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qrsalt/openapi/qrsalt-forms-api-openapi.yml
- filename: qrsalt-i-api-openapi.yml
  format: yaml
  label: QRSalt I API
  slug: qrsalt-i-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qrsalt/openapi/qrsalt-i-api-openapi.yml
- filename: qrsalt-qr-api-openapi.yml
  format: yaml
  label: QRSalt Qr API
  slug: qrsalt-qr-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qrsalt/openapi/qrsalt-qr-api-openapi.yml
- filename: qrsalt-qrsalt-api-api-openapi.yml
  format: yaml
  label: QRSalt QRSalt API
  slug: qrsalt-qrsalt-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qrsalt/openapi/qrsalt-qrsalt-api-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 16 years old, or old enough to enter a contract where you live, whichever is higher.
    type: individual
  - text: If you accept these terms for an organisation, you confirm you are allowed to bind it.
    type: business
  minimum_age:
    text: You must be at least 16 years old, or old enough to enter a contract where you live, whichever is higher.
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
name: QRSalt
provenance_date: '2026-11-10'
provider_name: QRSalt
provider_slug: qrsalt
slug: qrsalt-eligibility
source_date: '2026-11-10'
source_filename: qrsalt-eligibility.yml
source_heading: Eligibility
source_page: https://qrsalt.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: QRSalt\naid: qrsalt\nurl: https://qrsalt.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 16 years old, or old enough to enter a contract where you live, whichever is higher.\n- type: business\n  text: If you accept these terms for an organisation, you confirm you are allowed to bind it.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old, or old enough to enter a contract where\
  \ you live, whichever is higher.\n"
source_yaml_url: https://artifacts.apis.io/qrsalt/eligibility/qrsalt-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from QRSalt's own page on 2026-11-10.
synthetic: false
tags:
- QR Codes
- Barcodes
- Analytics
- Dynamic links
---
