---
api_specs:
- filename: paytabs-payments-api-openapi.yml
  format: yaml
  label: PayTabs Payments API
  slug: paytabs-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paytabs/openapi/paytabs-payments-api-openapi.yml
- filename: paytabs-transactions-api-openapi.yml
  format: yaml
  label: PayTabs Transactions API
  slug: paytabs-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paytabs/openapi/paytabs-transactions-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Products and features may vary by country (KSA, UAE, Egypt, Iraq, Jordan, Kuwait, Oman selectors shown).
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
name: PayTabs
provenance_date: '2026-11-10'
provider_name: PayTabs
provider_slug: paytabs
slug: paytabs-eligibility
source_date: '2026-11-10'
source_filename: paytabs-eligibility.yml
source_heading: Eligibility
source_page: https://ai.paytabs.com/en/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PayTabs\naid: paytabs\nurl: https://ai.paytabs.com/en/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Products and features may vary by country (KSA, UAE, Egypt, Iraq, Jordan, Kuwait, Oman selectors shown).\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/paytabs/eligibility/paytabs-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from PayTabs's own page on 2026-11-10.
synthetic: false
tags:
- Payments
- Payment Gateway
- Fintech
- MENA
- Saudi Arabia
- Cards
- mada
---
