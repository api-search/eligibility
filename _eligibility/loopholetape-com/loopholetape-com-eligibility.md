---
api_specs:
- filename: loopholetape-com-discovery-api-openapi.yml
  format: yaml
  label: loopholetape-com Discovery API
  slug: loopholetape-com-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loopholetape-com/openapi/loopholetape-com-discovery-api-openapi.yml
- filename: loopholetape-com-free-api-openapi.yml
  format: yaml
  label: loopholetape-com Free API
  slug: loopholetape-com-free-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loopholetape-com/openapi/loopholetape-com-free-api-openapi.yml
- filename: loopholetape-com-paid-api-openapi.yml
  format: yaml
  label: loopholetape-com Paid API
  slug: loopholetape-com-paid-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loopholetape-com/openapi/loopholetape-com-paid-api-openapi.yml
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
    approval_required: null
    kyb: null
    kyc: false
    text: We keep no accounts; a prepaid key holds a balance, not an identity.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: loopholetape-com
provenance_date: '2026-11-09'
provider_name: loopholetape-com
provider_slug: loopholetape-com
slug: loopholetape-com-eligibility
source_date: '2026-11-09'
source_filename: loopholetape-com-eligibility.yml
source_heading: Eligibility
source_page: https://loopholetape.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: loopholetape-com\naid: loopholetape-com\nurl: https://loopholetape.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: false\n  kyb: null\n  approval_required: null\n  text: We keep no accounts; a prepaid key holds a balance, not an identity.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/loopholetape-com/eligibility/loopholetape-com-eligibility.yml
stated_fields:
- verification
summary_line: 1 quoted statement, read from loopholetape-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cryptocurrency
- Solana
- Risk Management
---
