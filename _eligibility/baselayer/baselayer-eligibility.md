---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is for business use only.
    type: business
  minimum_age:
    text: By using the Service, Customer confirms that each person using it is at least 18 years old
    value: '18'
  restricted_uses:
  - summary: FCRA-covered purposes
    text: Customer will not use Baselayer Data for any purpose the FCRA covers, including to decide whether an individual is eligible for credit or insurance for personal, family or household purposes
  - summary: Harassment or harm
    text: Customer will not use Baselayer Data to harass, stalk, threaten or harm any person.
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
name: Baselayer
provenance_date: '2026-11-09'
provider_name: Baselayer
provider_slug: baselayer
slug: baselayer-eligibility
source_date: '2026-11-09'
source_filename: baselayer-eligibility.yml
source_heading: Eligibility
source_page: https://baselayer.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Baselayer\naid: baselayer\nurl: https://baselayer.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Service is for business use only.\nrestricted_uses:\n- summary: FCRA-covered purposes\n  text: Customer will not use Baselayer Data for any purpose the FCRA covers, including to decide whether an individual\n    is eligible for credit or insurance for personal, family or household purposes\n- summary: Harassment or harm\n  text: Customer will not use Baselayer Data to harass, stalk, threaten or harm any person.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: By using the Service, Customer confirms that each person using it is at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/baselayer/eligibility/baselayer-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Baselayer's own page on 2026-11-09.
synthetic: false
tags:
- Business
- Identity Verification
- Risk Management
- Fintech
---
