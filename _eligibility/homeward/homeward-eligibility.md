---
api_specs:
- filename: homeward-buybox-api-openapi.yml
  format: yaml
  label: Homeward Buybox API
  slug: homeward-buybox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/homeward/openapi/homeward-buybox-api-openapi.yml
- filename: homeward-finalization-api-openapi.yml
  format: yaml
  label: Homeward Finalization API
  slug: homeward-finalization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/homeward/openapi/homeward-finalization-api-openapi.yml
- filename: homeward-offer-requests-api-openapi.yml
  format: yaml
  label: Homeward Offer Requests API
  slug: homeward-offer-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/homeward/openapi/homeward-offer-requests-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Applicable terms, conditions, and eligibility requirements are subject to change and not all products and services are available in all geographic areas.
  minimum_age:
    text: The Services are not for use by users under the age of 18.
    value: '18'
  restricted_uses:
  - summary: Personal non-commercial use
    text: Unless stated otherwise, the Services are for your personal and non-commercial use only.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Your eligibility for particular products or services is subject to Homeward's final approval in its sole and absolute discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Homeward
provenance_date: '2026-11-09'
provider_name: Homeward
provider_slug: homeward
slug: homeward-eligibility
source_date: '2026-11-09'
source_filename: homeward-eligibility.yml
source_heading: Eligibility
source_page: https://www.homeward.com/legalese/terms-conditions-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Homeward\naid: homeward\nurl: https://www.homeward.com/legalese/terms-conditions-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Applicable terms, conditions, and eligibility requirements are subject to change and not all products and\n    services are available in all geographic areas.\nentity_types: []\nrestricted_uses:\n- summary: Personal non-commercial use\n  text: Unless stated otherwise, the Services are for your personal and non-commercial use only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Your eligibility for particular products\
  \ or services is subject to Homeward's final approval in its sole\n    and absolute discretion.\nminimum_age:\n  value: '18'\n  text: The Services are not for use by users under the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/homeward/eligibility/homeward-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Homeward's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Real Estate
- Home Finance
- Mortgage
- PropTech
- Cash Offer
- Title
- Lending
---
