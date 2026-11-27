---
api_specs:
- filename: rendlet-com-checkout-api-openapi.yml
  format: yaml
  label: rendlet-com Checkout API
  slug: rendlet-com-checkout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rendlet-com/openapi/rendlet-com-checkout-api-openapi.yml
- filename: rendlet-com-pdf-api-openapi.yml
  format: yaml
  label: rendlet-com PDF API
  slug: rendlet-com-pdf-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rendlet-com/openapi/rendlet-com-pdf-api-openapi.yml
- filename: rendlet-com-signup-api-openapi.yml
  format: yaml
  label: rendlet-com Signup API
  slug: rendlet-com-signup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rendlet-com/openapi/rendlet-com-signup-api-openapi.yml
- filename: rendlet-com-templates-api-openapi.yml
  format: yaml
  label: rendlet-com Templates API
  slug: rendlet-com-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rendlet-com/openapi/rendlet-com-templates-api-openapi.yml
- filename: rendlet-com-usage-api-openapi.yml
  format: yaml
  label: rendlet-com Usage API
  slug: rendlet-com-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rendlet-com/openapi/rendlet-com-usage-api-openapi.yml
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
  restricted_uses:
  - summary: sandbox key not for production
    text: The sandbox key is limited, watermarked and not for production use.
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
name: rendlet-com
provenance_date: '2026-11-10'
provider_name: rendlet-com
provider_slug: rendlet-com
slug: rendlet-com-eligibility
source_date: '2026-11-10'
source_filename: rendlet-com-eligibility.yml
source_heading: Eligibility
source_page: https://rendlet.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: rendlet-com\naid: rendlet-com\nurl: https://rendlet.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: sandbox key not for production\n  text: The sandbox key is limited, watermarked and not for production use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/rendlet-com/eligibility/rendlet-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from rendlet-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- PDF
- Document Generation
- Software-as-a-Service
- Artificial Intelligence
---
