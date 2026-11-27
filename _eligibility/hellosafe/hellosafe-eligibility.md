---
api_specs:
- filename: hellosafe-conversion-api-openapi.yml
  format: yaml
  label: HelloSafe Conversion API
  slug: hellosafe-conversion-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hellosafe/openapi/hellosafe-conversion-api-openapi.yml
- filename: hellosafe-links-api-openapi.yml
  format: yaml
  label: HelloSafe Links API
  slug: hellosafe-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hellosafe/openapi/hellosafe-links-api-openapi.yml
- filename: hellosafe-quotes-api-openapi.yml
  format: yaml
  label: HelloSafe Quotes API
  slug: hellosafe-quotes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hellosafe/openapi/hellosafe-quotes-api-openapi.yml
- filename: hellosafe-coach-api-openapi.yml
  format: yaml
  label: HelloSafe Coach API
  slug: hellosafe-coach-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hellosafe/openapi/hellosafe-coach-api-openapi.yml
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
    approval_required: true
    kyb: null
    kyc: null
    text: All applications are subject to validation by our team within 24 business hours. HelloSafe reserves the right to decline an application without giving reasons.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: HelloSafe
provenance_date: '2026-11-09'
provider_name: HelloSafe
provider_slug: hellosafe
slug: hellosafe-eligibility
source_date: '2026-11-09'
source_filename: hellosafe-eligibility.yml
source_heading: Eligibility
source_page: https://atlas.hellosafe.com/legal/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HelloSafe\naid: hellosafe\nurl: https://atlas.hellosafe.com/legal/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: All applications are subject to validation by our team within 24 business hours. HelloSafe reserves the\n    right to decline an application without giving reasons.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/hellosafe/eligibility/hellosafe-eligibility.yml
stated_fields:
- verification
summary_line: 1 quoted statement, read from HelloSafe's own page on 2026-11-09.
synthetic: false
tags:
- Travel Insurance
- Insurance Distribution
- Pricing
- Travel
---
