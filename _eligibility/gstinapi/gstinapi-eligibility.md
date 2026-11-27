---
api_specs:
- filename: gstinapi-bulk-api-openapi.yml
  format: yaml
  label: GSTIN API Bulk API
  slug: gstinapi-bulk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gstinapi/openapi/gstinapi-bulk-api-openapi.yml
- filename: gstinapi-verification-api-openapi.yml
  format: yaml
  label: GSTIN API Verification API
  slug: gstinapi-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gstinapi/openapi/gstinapi-verification-api-openapi.yml
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
  - summary: Unlawful use
    text: Use the service for any unlawful purpose.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: New users receive 20 free credits after verifying their email address.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: GSTIN API
provenance_date: '2026-11-09'
provider_name: GSTIN API
provider_slug: gstinapi
slug: gstinapi-eligibility
source_date: '2026-11-09'
source_filename: gstinapi-eligibility.yml
source_heading: Eligibility
source_page: https://gstinapi.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: GSTIN API\naid: gstinapi\nurl: https://gstinapi.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful use\n  text: Use the service for any unlawful purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: New users receive 20 free credits after verifying their email address.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/gstinapi/eligibility/gstinapi-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from GSTIN API's own page on 2026-11-09.
synthetic: false
tags:
- Company
- GST
- India
- Taxation
---
