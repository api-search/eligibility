---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - AU
    text: The material on this site is published by us and is intended for use in Australia. The site is not intended for use outside Australia.
  entity_types:
  - text: This site is a business and commercial site.
    type: business
  minimum_age:
    text: It is, therefore, not intended for persons under the age of 18.
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
name: PSC Insurance
provenance_date: '2026-11-10'
provider_name: PSC Insurance
provider_slug: psc-insurance
slug: psc-insurance-eligibility
source_date: '2026-11-10'
source_filename: psc-insurance-eligibility.yml
source_heading: Eligibility
source_page: https://www.pscinsurance.com.au/terms-of-use-statement/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PSC Insurance\naid: psc-insurance\nurl: https://www.pscinsurance.com.au/terms-of-use-statement/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - AU\n  excluded: []\n  text: The material on this site is published by us and is intended for use in Australia. The site is not intended\n    for use outside Australia.\nentity_types:\n- type: business\n  text: This site is a business and commercial site.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: It is, therefore, not intended for persons under the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/psc-insurance/eligibility/psc-insurance-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from PSC Insurance's own page on 2026-11-10.
synthetic: false
tags:
- Insurance
- Australia
- Brokerage
- Insurance Brokerage
- Property and Casualty
- Commercial Insurance
- Cyber Insurance
- Intermediary
---
