---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Invygo will not trade with or provide any services to OFAC and sanctioned countries.
  entity_types:
  - text: a person or company that contacts, engages and/or aims to lease a Vehicle or Vehicles from a Vendor through the Platform and/or App
    type: individual
  - text: a person or company that contacts, engages and/or aims to lease a Vehicle or Vehicles from a Vendor through the Platform and/or App
    type: business
  minimum_age:
    text: You represent and acknowledge that you are over the age of 18.
    value: '18'
  restricted_uses:
  - summary: Users under 18 barred
    text: we do not permit any Clients under 18 to use our Service.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: for the purpose of assessing whether you meet the eligibility criteria for the Service.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Invygo
provenance_date: '2026-11-09'
provider_name: Invygo
provider_slug: invygo
slug: invygo-eligibility
source_date: '2026-11-09'
source_filename: invygo-eligibility.yml
source_heading: Eligibility
source_page: https://www.invygo.com/default/tc
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Invygo\naid: invygo\nurl: https://www.invygo.com/default/tc\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Invygo will not trade with or provide any services to OFAC and sanctioned countries.\nentity_types:\n- type: individual\n  text: a person or company that contacts, engages and/or aims to lease a Vehicle or Vehicles from a Vendor through\n    the Platform and/or App\n- type: business\n  text: a person or company that contacts, engages and/or aims to lease a Vehicle or Vehicles from a Vendor through\n    the Platform and/or App\nrestricted_uses:\n- summary:\
  \ Users under 18 barred\n  text: we do not permit any Clients under 18 to use our Service.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: for the purpose of assessing whether you meet the eligibility criteria for the Service.\nminimum_age:\n  value: '18'\n  text: You represent and acknowledge that you are over the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/invygo/eligibility/invygo-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Invygo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Car Subscription
- Car Rental
- Mobility
- Automotive
- Transportation
- Mobile App
- United Arab Emirates
---
