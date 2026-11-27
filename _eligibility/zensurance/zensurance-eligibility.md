---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Online Properties and Products (as defined above) may not be appropriate or available for use in some non-Canadian jurisdictions.
  minimum_age:
    text: you must be over the age of majority in your province
    value: null
  restricted_uses:
  - summary: Sanctions and unlawful use
    text: Zensurance reserves the right to immediately suspend or terminate its services (in whole or in part), including initiating the cancellation of any insurance policy, if we determine that continuing to serve you could violate applicable law or expose Zensurance
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
name: Zensurance
provenance_date: '2026-11-10'
provider_name: Zensurance
provider_slug: zensurance
slug: zensurance-eligibility
source_date: '2026-11-10'
source_filename: zensurance-eligibility.yml
source_heading: Eligibility
source_page: https://www.zensurance.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zensurance\naid: zensurance\nurl: https://www.zensurance.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Online Properties and Products (as defined above) may not be appropriate or available for use in some\n    non-Canadian jurisdictions.\nentity_types: []\nrestricted_uses:\n- summary: Sanctions and unlawful use\n  text: Zensurance reserves the right to immediately suspend or terminate its services (in whole or in part), including\n    initiating the cancellation of any insurance policy, if we determine that continuing to serve you could violate\n    applicable\
  \ law or expose Zensurance\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you must be over the age of majority in your province\n"
source_yaml_url: https://artifacts.apis.io/zensurance/eligibility/zensurance-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Zensurance's own page on 2026-11-10.
synthetic: false
tags:
- Insurance
- Canada
- Insurtech
- Brokerage
- Property and Casualty
- Commercial Insurance
- Small Business Insurance
- Cyber Insurance
- Digital Brokerage
---
