---
api_specs:
- filename: curagent-io-openapi-generated.yml
  format: yaml
  label: curagent-io API
  slug: curagent-io-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/curagent-io/openapi/_ae-authored/curagent-io-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You means the individual accessing or using the Service, or the company, or other legal entity on behalf of which such individual is accessing or using the Service
    type: business
  minimum_age:
    text: You represent that you are over the age of 18. The Company does not permit those under 18 to use the Service.
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
name: curagent-io
provenance_date: '2026-11-09'
provider_name: curagent-io
provider_slug: curagent-io
slug: curagent-io-eligibility
source_date: '2026-11-09'
source_filename: curagent-io-eligibility.yml
source_heading: Eligibility
source_page: https://www.termsfeed.com/live/d0a757d0-f16a-4978-9aa0-d9a80e0ecbdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: curagent-io\naid: curagent-io\nurl: https://www.termsfeed.com/live/d0a757d0-f16a-4978-9aa0-d9a80e0ecbdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: You means the individual accessing or using the Service, or the company, or other legal entity on behalf\n    of which such individual is accessing or using the Service\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent that you are over the age of 18. The Company does not permit those\
  \ under 18 to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/curagent-io/eligibility/curagent-io-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from curagent-io's own page on 2026-11-09.
synthetic: false
tags:
- Real Estate
- Title
- Risk Analysis
- Document Processing
- Company
---
