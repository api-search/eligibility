---
api_specs:
- filename: filingfirehose-com-billing-api-openapi.yml
  format: yaml
  label: filingfirehose-com Billing API
  slug: filingfirehose-com-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filingfirehose-com/openapi/filingfirehose-com-billing-api-openapi.yml
- filename: filingfirehose-com-filings-api-openapi.yml
  format: yaml
  label: filingfirehose-com Filings API
  slug: filingfirehose-com-filings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filingfirehose-com/openapi/filingfirehose-com-filings-api-openapi.yml
- filename: filingfirehose-com-meta-api-openapi.yml
  format: yaml
  label: filingfirehose-com Meta API
  slug: filingfirehose-com-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filingfirehose-com/openapi/filingfirehose-com-meta-api-openapi.yml
- filename: filingfirehose-com-public-api-openapi.yml
  format: yaml
  label: filingfirehose-com Public API
  slug: filingfirehose-com-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filingfirehose-com/openapi/filingfirehose-com-public-api-openapi.yml
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
  - summary: Harassment or unlawful targeting
    text: Use the data to harass, defame, or unlawfully target any individual or entity
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
name: filingfirehose-com
provenance_date: '2026-11-09'
provider_name: filingfirehose-com
provider_slug: filingfirehose-com
slug: filingfirehose-com-eligibility
source_date: '2026-11-09'
source_filename: filingfirehose-com-eligibility.yml
source_heading: Eligibility
source_page: https://filingfirehose.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: filingfirehose-com\naid: filingfirehose-com\nurl: https://filingfirehose.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Harassment or unlawful targeting\n  text: Use the data to harass, defame, or unlawfully target any individual or entity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/filingfirehose-com/eligibility/filingfirehose-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from filingfirehose-com's own page on 2026-11-09.
synthetic: false
tags:
- SEC
- EDGAR
- Finance
- Data API
- JSON
---
