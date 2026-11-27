---
api_specs:
- filename: cumulio-authorize-api-openapi.yml
  format: yaml
  label: Cumulio Authorize API
  slug: cumulio-authorize-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cumulio/openapi/cumulio-authorize-api-openapi.yml
- filename: cumulio-datasets-api-openapi.yml
  format: yaml
  label: Cumulio Datasets API
  slug: cumulio-datasets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cumulio/openapi/cumulio-datasets-api-openapi.yml
- filename: cumulio-exchange-api-openapi.yml
  format: yaml
  label: Cumulio Exchange API
  slug: cumulio-exchange-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cumulio/openapi/cumulio-exchange-api-openapi.yml
- filename: cumulio-query-api-openapi.yml
  format: yaml
  label: Cumulio Query API
  slug: cumulio-query-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cumulio/openapi/cumulio-query-api-openapi.yml
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
  - summary: Unlawful or infringing use
    text: use the Licensed Products in any way that (i) is unlawful, illegal, fraudulent or harmful, or in connection with any unlawful, illegal, fraudulent or harmful purpose or activity
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
name: Cumulio
provenance_date: '2026-11-09'
provider_name: Cumulio
provider_slug: cumulio
slug: cumulio-eligibility
source_date: '2026-11-09'
source_filename: cumulio-eligibility.yml
source_heading: Eligibility
source_page: https://www.luzmo.com/information-pages/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cumulio\naid: cumulio\nurl: https://www.luzmo.com/information-pages/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or infringing use\n  text: use the Licensed Products in any way that (i) is unlawful, illegal, fraudulent or harmful, or in connection\n    with any unlawful, illegal, fraudulent or harmful purpose or activity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cumulio/eligibility/cumulio-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Cumulio's own page on 2026-11-09.
synthetic: false
tags:
- Company
---
