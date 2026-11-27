---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: PRICES ARE ESTIMATIONS AND ARE NOT OFFICIAL AND THAT YOU MAY NOT BE OFFERED A QUOTE DUE TO ELIGIBILITY REQUIREMENTS, INCLUDING BUT NOT LIMITED TO DIFFERENCES BASED ON MEDICAL HISTORY, DISCOUNTS, AND THE STATE IN WHICH YOU RESIDE.
  entity_types:
  - text: The SimplyInsured Service is for individuals trying to find insurance information for themselves, their families, and their friends
    type: individual
  minimum_age:
    text: You affirm that you are either more than 18 years of age, or an emancipated minor, or possess legal parental or guardian consent
    value: '18'
  restricted_uses:
  - summary: Commercial use restricted
    text: If you are looking for insurance information for a commercial purpose (for example, if you are an insurance agent), you may not use SimplyInsured to find information and then use that information to bind policies through another website or service.
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
name: Simplyinsured
provenance_date: '2026-11-10'
provider_name: Simplyinsured
provider_slug: simplyinsured
slug: simplyinsured-eligibility
source_date: '2026-11-10'
source_filename: simplyinsured-eligibility.yml
source_heading: Eligibility
source_page: https://get.simplyinsured.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Simplyinsured\naid: simplyinsured\nurl: https://get.simplyinsured.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: PRICES ARE ESTIMATIONS AND ARE NOT OFFICIAL AND THAT YOU MAY NOT BE OFFERED A QUOTE DUE TO ELIGIBILITY REQUIREMENTS,\n    INCLUDING BUT NOT LIMITED TO DIFFERENCES BASED ON MEDICAL HISTORY, DISCOUNTS, AND THE STATE IN WHICH YOU RESIDE.\nentity_types:\n- type: individual\n  text: The SimplyInsured Service is for individuals trying to find insurance information for themselves, their\n    families, and their friends\nrestricted_uses:\n- summary: Commercial\
  \ use restricted\n  text: If you are looking for insurance information for a commercial purpose (for example, if you are an insurance\n    agent), you may not use SimplyInsured to find information and then use that information to bind policies through\n    another website or service.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You affirm that you are either more than 18 years of age, or an emancipated minor, or possess legal parental\n    or guardian consent\n"
source_yaml_url: https://artifacts.apis.io/simplyinsured/eligibility/simplyinsured-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Simplyinsured's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health Insurance
- Insurance
- Employee Benefits
- Small Business
- Insurtech
- Health Benefits
---
