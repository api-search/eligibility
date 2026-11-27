---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: In these Terms, "Customer" means the person (who may be a natural person, company or other legal entity capable of being a party to a contract) that registers for the right to access and use the 9S Platform.
    type: individual
  - text: if the Customer is a company or other legal entity, a person authorized to enter into this contract on the Company's behalf
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Use must be for normal business purposes
    text: strictly for the Customer's normal business purposes
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
name: 9Spokes
provenance_date: '2026-11-09'
provider_name: 9Spokes
provider_slug: 9spokes
slug: 9spokes-eligibility
source_date: '2026-11-09'
source_filename: 9spokes-eligibility.yml
source_heading: Eligibility
source_page: https://9spokes.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 9Spokes\naid: 9spokes\nurl: https://9spokes.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: In these Terms, \"Customer\" means the person (who may be a natural person, company or other legal entity\n    capable of being a party to a contract) that registers for the right to access and use the 9S Platform.\n- type: business\n  text: if the Customer is a company or other legal entity, a person authorized to enter into this contract on the\n    Company's behalf\nrestricted_uses:\n- summary: Use must be for normal\
  \ business purposes\n  text: strictly for the Customer's normal business purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/9spokes/eligibility/9spokes-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from 9Spokes's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Banking
- Small Business
- Data Analytics
---
