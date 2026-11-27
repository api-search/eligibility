---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served:
    - CA
    text: CAA Insurance products and services described on the Website relate to products and services within Canada only, and are only made available in jurisdictions within Canada where they may be lawfully offered for sale.
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
name: CAA Insurance
provenance_date: '2026-11-09'
provider_name: CAA Insurance
provider_slug: caa-insurance
slug: caa-insurance-eligibility
source_date: '2026-11-09'
source_filename: caa-insurance-eligibility.yml
source_heading: Eligibility
source_page: https://caainsurancecompany.ca/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CAA Insurance\naid: caa-insurance\nurl: https://caainsurancecompany.ca/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - CA\n  excluded: []\n  text: CAA Insurance products and services described on the Website relate to products and services within Canada\n    only, and are only made available in jurisdictions within Canada where they may be lawfully offered for sale.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/caa-insurance/eligibility/caa-insurance-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from CAA Insurance's own page on 2026-11-09.
synthetic: false
tags:
- Insurance
- Canada
- Property and Casualty
- Auto Insurance
- Home Insurance
- Carrier
- Personal Lines
- Telematics
---
