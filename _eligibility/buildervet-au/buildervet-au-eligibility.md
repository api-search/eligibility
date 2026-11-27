---
api_specs:
- filename: buildervet-au-api-openapi.yml
  format: yaml
  label: BuilderVet API API
  slug: buildervet-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buildervet-au/openapi/_original/buildervet-au-api-openapi.yml
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
  - summary: Credit, insurance, employment decisions
    text: Do not use results for credit, insurance or employment decisions about an individual.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You sign in with an emailed link.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: BuilderVet
provenance_date: '2026-11-09'
provider_name: BuilderVet
provider_slug: buildervet-au
slug: buildervet-au-eligibility
source_date: '2026-11-09'
source_filename: buildervet-au-eligibility.yml
source_heading: Eligibility
source_page: https://buildervet.au/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BuilderVet\naid: buildervet-au\nurl: https://buildervet.au/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Credit, insurance, employment decisions\n  text: Do not use results for credit, insurance or employment decisions about an individual.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You sign in with an emailed link.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/buildervet-au/eligibility/buildervet-au-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from BuilderVet's own page on 2026-11-09.
synthetic: false
tags:
- Company
---
