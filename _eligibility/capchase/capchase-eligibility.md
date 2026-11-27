---
api_specs:
- filename: capchase-pay-api-openapi.yml
  format: yaml
  label: Capchase Pay API
  slug: capchase-pay-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capchase/openapi/capchase-pay-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that (i) you are not located in a country that is subject to the United States government embargo, or that has been designated by the United States government as a "terrorist supporting" country
  minimum_age:
    text: In any case, you affirm that you are at least 13 years of age, as the Website is not intended for children under 13.
    value: '13'
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
name: Capchase
provenance_date: '2026-11-09'
provider_name: Capchase
provider_slug: capchase
slug: capchase-eligibility
source_date: '2026-11-09'
source_filename: capchase-eligibility.yml
source_heading: Eligibility
source_page: https://www.capchase.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Capchase\naid: capchase\nurl: https://www.capchase.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that (i) you are not located in a country that is subject to the United States\n    government embargo, or that has been designated by the United States government as a \"terrorist supporting\"\n    country\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: In any case, you affirm that you are at least 13 years of age, as the Website\
  \ is not intended for children\n    under 13.\n"
source_yaml_url: https://artifacts.apis.io/capchase/eligibility/capchase-eligibility.yml
stated_fields:
- countries
- minimum_age
summary_line: 2 quoted statements, read from Capchase's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Payments
- Embedded Finance
- Financing
- B2B SaaS
- Revenue Financing
- Buy Now Pay Later
- KYB
- Underwriting
---
