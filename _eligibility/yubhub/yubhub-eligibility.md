---
api_specs:
- filename: yubhub-openapi-generated.yml
  format: yaml
  label: YubHub API
  slug: yubhub-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yubhub/openapi/_ae-authored/yubhub-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 18 years old to use the Service.
    value: '18'
  restricted_uses:
  - summary: Unlawful purpose
    text: Use the Service for any unlawful purpose
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
name: YubHub
provenance_date: '2026-11-10'
provider_name: YubHub
provider_slug: yubhub
slug: yubhub-eligibility
source_date: '2026-11-10'
source_filename: yubhub-eligibility.yml
source_heading: Eligibility
source_page: https://yubhub.co/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: YubHub\naid: yubhub\nurl: https://yubhub.co/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful purpose\n  text: Use the Service for any unlawful purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/yubhub/eligibility/yubhub-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from YubHub's own page on 2026-11-10.
synthetic: false
tags:
- JobFeed
- Recruiting
- United Kingdom
- Data Enrichment
---
