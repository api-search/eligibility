---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: Our Site is for people residing in the United Kingdom.
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
name: flatfair
provenance_date: '2026-11-09'
provider_name: flatfair
provider_slug: flatfair
slug: flatfair-eligibility
source_date: '2026-11-09'
source_filename: flatfair-eligibility.yml
source_heading: Eligibility
source_page: https://www.flatfair.co.uk/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: flatfair\naid: flatfair\nurl: https://www.flatfair.co.uk/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: Our Site is for people residing in the United Kingdom.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/flatfair/eligibility/flatfair-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from flatfair's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- PropTech
- Rentals
- Deposits
- Tenancy
- Real Estate
- United Kingdom
---
