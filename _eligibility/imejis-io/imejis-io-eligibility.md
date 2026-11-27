---
api_specs:
- filename: imejis-io-analytics-api-openapi.yml
  format: yaml
  label: imejis-io Analytics API
  slug: imejis-io-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imejis-io/openapi/imejis-io-analytics-api-openapi.yml
- filename: imejis-io-designs-api-openapi.yml
  format: yaml
  label: imejis-io Designs API
  slug: imejis-io-designs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imejis-io/openapi/imejis-io-designs-api-openapi.yml
- filename: imejis-io-keys-api-openapi.yml
  format: yaml
  label: imejis-io Keys API
  slug: imejis-io-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imejis-io/openapi/imejis-io-keys-api-openapi.yml
- filename: imejis-io-render-api-openapi.yml
  format: yaml
  label: imejis-io Render API
  slug: imejis-io-render-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/imejis-io/openapi/imejis-io-render-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and able to form a binding contract.
    type: individual
  minimum_age:
    text: You must be at least 18 years old and able to form a binding contract.
    value: '18'
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
name: imejis-io
provenance_date: '2026-11-09'
provider_name: imejis-io
provider_slug: imejis-io
slug: imejis-io-eligibility
source_date: '2026-11-09'
source_filename: imejis-io-eligibility.yml
source_heading: Eligibility
source_page: https://www.imejis.io/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: imejis-io\naid: imejis-io\nurl: https://www.imejis.io/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and able to form a binding contract.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and able to form a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/imejis-io/eligibility/imejis-io-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from imejis-io's own page on 2026-11-09.
synthetic: false
tags:
- Company
---
