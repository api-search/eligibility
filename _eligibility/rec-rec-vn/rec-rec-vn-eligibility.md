---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'Country refers to: Andhra Pradesh, India'
  entity_types:
  - text: You represent that you are over the age of 18.
    type: individual
  minimum_age:
    text: You represent that you are over the age of 18. The Company does not permit those under 18 to use the Service.
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
name: Ecobites Pte. Ltd.
provenance_date: '2026-11-10'
provider_name: Ecobites Pte. Ltd.
provider_slug: rec-rec-vn
slug: rec-rec-vn-eligibility
source_date: '2026-11-10'
source_filename: rec-rec-vn-eligibility.yml
source_heading: Eligibility
source_page: https://www.ecobites.net/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ecobites Pte. Ltd.\naid: rec-rec-vn\nurl: https://www.ecobites.net/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 'Country refers to: Andhra Pradesh, India'\nentity_types:\n- type: individual\n  text: You represent that you are over the age of 18.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent that you are over the age of 18. The Company does not permit those under 18 to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/rec-rec-vn/eligibility/rec-rec-vn-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Ecobites Pte. Ltd.'s own page on 2026-11-10.
synthetic: false
tags:
- Company
- Food Tech
- Singapore
- Marketplace
---
