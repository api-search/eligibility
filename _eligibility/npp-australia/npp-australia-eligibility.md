---
api_specs:
- filename: npp-australia-openapi-generated.yml
  format: yaml
  label: NPP Australia (AP+) API
  slug: npp-australia-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/npp-australia/openapi/_ae-authored/npp-australia-openapi-generated.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If you access this website from outside Australia, you are solely responsible for ensuring compliance with your local laws
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
name: NPP Australia (AP+)
provenance_date: '2026-11-10'
provider_name: NPP Australia (AP+)
provider_slug: npp-australia
slug: npp-australia-eligibility
source_date: '2026-11-10'
source_filename: npp-australia-eligibility.yml
source_heading: Eligibility
source_page: https://www.auspayplus.com.au/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: NPP Australia (AP+)\naid: npp-australia\nurl: https://www.auspayplus.com.au/terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: If you access this website from outside Australia, you are solely responsible for ensuring compliance with\n    your local laws\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/npp-australia/eligibility/npp-australia-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from NPP Australia (AP+)'s own page on 2026-11-10.
synthetic: false
tags:
- Payments
- Australia
- Real-Time Payments
- Account-to-Account
- ISO 20022
- Payment Scheme
- Payment Rails
- PayTo
- PayID
- Open Banking
---
