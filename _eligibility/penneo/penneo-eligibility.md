---
api_specs:
- filename: penneo-case-file-creation-api-openapi.yml
  format: yaml
  label: Penneo Case File Creation API
  slug: penneo-case-file-creation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/penneo/openapi/penneo-case-file-creation-api-openapi.yml
- filename: penneo-oauth-api-openapi.yml
  format: yaml
  label: Penneo OAuth API
  slug: penneo-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/penneo/openapi/penneo-oauth-api-openapi.yml
- filename: penneo-penneo-collect-api-api-openapi.yml
  format: yaml
  label: Penneo Penneo Collect API
  slug: penneo-penneo-collect-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/penneo/openapi/penneo-penneo-collect-api-api-openapi.yml
- filename: penneo-queue-status-check-api-openapi.yml
  format: yaml
  label: Penneo Queue Status Check API
  slug: penneo-queue-status-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/penneo/openapi/penneo-queue-status-check-api-openapi.yml
- filename: penneo-version-api-openapi.yml
  format: yaml
  label: Penneo Version API
  slug: penneo-version-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/penneo/openapi/penneo-version-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the entity placing an order for accessing the Penneo Sign Platform (hereinafter referred to as the “Customer”)
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal or unethical content
    text: using the Platform to store or transmit any material containing illegal or unethical content
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
name: Penneo
provenance_date: '2026-11-10'
provider_name: Penneo
provider_slug: penneo
slug: penneo-eligibility
source_date: '2026-11-10'
source_filename: penneo-eligibility.yml
source_heading: Eligibility
source_page: https://penneo.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Penneo\naid: penneo\nurl: https://penneo.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the entity placing an order for accessing the Penneo Sign Platform (hereinafter referred to as the “Customer”)\nrestricted_uses:\n- summary: Illegal or unethical content\n  text: using the Platform to store or transmit any material containing illegal or unethical content\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/penneo/eligibility/penneo-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Penneo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Digital Signing
- eIDAS
- Compliance
---
