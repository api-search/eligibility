---
api_specs:
- filename: cloudidr-external-api-openapi.yml
  format: yaml
  label: Cloudidr External API
  slug: cloudidr-external-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudidr/openapi/cloudidr-external-api-openapi.yml
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
  - summary: DRCS exclusive to DR events
    text: DRCS is specifically designed and must be used exclusively for DR events.
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
name: Cloudidr
provenance_date: '2026-11-09'
provider_name: Cloudidr
provider_slug: cloudidr
slug: cloudidr-eligibility
source_date: '2026-11-09'
source_filename: cloudidr-eligibility.yml
source_heading: Eligibility
source_page: https://www.cloudidr.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cloudidr\naid: cloudidr\nurl: https://www.cloudidr.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: DRCS exclusive to DR events\n  text: DRCS is specifically designed and must be used exclusively for DR events.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cloudidr/eligibility/cloudidr-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Cloudidr's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Identity and Access Management
- Cloud
- Security
- Artificial Intelligence
- FinOps
---
