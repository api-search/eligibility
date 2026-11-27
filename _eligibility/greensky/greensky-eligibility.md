---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you are not located in a country that is subject to a U.S. Government embargo
  entity_types:
  - text: The Services are intended solely for natural persons who are eighteen (18) years of age or older
    type: individual
  minimum_age:
    text: The Services are for Use by Individuals 18 years of age and older.
    value: '18'
  restricted_uses:
  - summary: Benchmarking or competitive use
    text: Access, use, or monitor our Services for benchmarking or any direct competitive purposes.
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
name: GreenSky
provenance_date: '2026-11-09'
provider_name: GreenSky
provider_slug: greensky
slug: greensky-eligibility
source_date: '2026-11-09'
source_filename: greensky-eligibility.yml
source_heading: Eligibility
source_page: https://www.greensky.com/terms/website_terms_of_use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: GreenSky\naid: greensky\nurl: https://www.greensky.com/terms/website_terms_of_use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: you are not located in a country that is subject to a U.S. Government embargo\nentity_types:\n- type: individual\n  text: The Services are intended solely for natural persons who are eighteen (18) years of age or older\nrestricted_uses:\n- summary: Benchmarking or competitive use\n  text: Access, use, or monitor our Services for benchmarking or any direct competitive purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are for Use by Individuals 18 years of age and older.\n"
source_yaml_url: https://artifacts.apis.io/greensky/eligibility/greensky-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from GreenSky's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Consumer Financing
- Point of Sale Lending
- Home Improvement
- healthcare-financing
- Loan Servicing
- Merchant Services
---
