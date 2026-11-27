---
api_specs:
- filename: lettance-com-openapi.json
  format: json
  label: Lettance Public API
  slug: lettance-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lettance-com/openapi/lettance-com-openapi.json
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The service is software for landlords of privately rented homes in England.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No harassment, unlawful discrimination or illegal use
    text: Do not use the service to harass tenants, to discriminate unlawfully, or to break the law.
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
name: lettance-com
provenance_date: '2026-11-09'
provider_name: lettance-com
provider_slug: lettance-com
slug: lettance-com-eligibility
source_date: '2026-11-09'
source_filename: lettance-com-eligibility.yml
source_heading: Eligibility
source_page: https://lettance.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: lettance-com\naid: lettance-com\nurl: https://lettance.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The service is software for landlords of privately rented homes in England.\nentity_types: []\nrestricted_uses:\n- summary: No harassment, unlawful discrimination or illegal use\n  text: Do not use the service to harass tenants, to discriminate unlawfully, or to break the law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/lettance-com/eligibility/lettance-com-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from lettance-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Leasing
- Subscription
- Automation
---
