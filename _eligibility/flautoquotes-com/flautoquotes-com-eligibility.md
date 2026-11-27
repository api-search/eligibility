---
api_specs:
- filename: flautoquotes-com-eligibility-api-openapi.yml
  format: yaml
  label: flautoquotes-com Eligibility API
  slug: flautoquotes-com-eligibility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flautoquotes-com/openapi/flautoquotes-com-eligibility-api-openapi.yml
- filename: flautoquotes-com-quotes-api-openapi.yml
  format: yaml
  label: flautoquotes-com Quotes API
  slug: flautoquotes-com-quotes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flautoquotes-com/openapi/flautoquotes-com-quotes-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Contact details leave only with the consumer's explicit consent, to licensed agents, in the scope granted.
    type: individual
  minimum_age:
    text: null
    value: null
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
name: flautoquotes-com
provenance_date: '2026-11-09'
provider_name: flautoquotes-com
provider_slug: flautoquotes-com
slug: flautoquotes-com-eligibility
source_date: '2026-11-09'
source_filename: flautoquotes-com-eligibility.yml
source_heading: Eligibility
source_page: https://flautoquotes.com/v1/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: flautoquotes-com\naid: flautoquotes-com\nurl: https://flautoquotes.com/v1/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Contact details leave only with the consumer's explicit consent, to licensed agents, in the scope granted.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/flautoquotes-com/eligibility/flautoquotes-com-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from flautoquotes-com's own page on 2026-11-09.
synthetic: false
tags:
- Insurance
- Auto
- Quotes
- Florida
- Marketplace
---
