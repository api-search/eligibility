---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Neither the website/services nor the information contained therein are addressed to or intended for users in countries or jurisdictions, in which such publication is forbidden or unlawful.
  entity_types:
  - text: The registration further presupposes that the user truthfully transmits the data requested in the registration form and is an unrestrictedly contractually capable natural person over 18 years of age.
    type: individual
  minimum_age:
    text: is an unrestrictedly contractually capable natural person over 18 years of age.
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
name: BrokerFlat
provenance_date: '2026-11-09'
provider_name: BrokerFlat
provider_slug: brokerflat-com
slug: brokerflat-com-eligibility
source_date: '2026-11-09'
source_filename: brokerflat-com-eligibility.yml
source_heading: Eligibility
source_page: https://brokerflat.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BrokerFlat\naid: brokerflat-com\nurl: https://brokerflat.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Neither the website/services nor the information contained therein are addressed to or intended for users\n    in countries or jurisdictions, in which such publication is forbidden or unlawful.\nentity_types:\n- type: individual\n  text: The registration further presupposes that the user truthfully transmits the data requested in the registration\n    form and is an unrestrictedly contractually capable natural person over 18 years of age.\nrestricted_uses:\
  \ []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: is an unrestrictedly contractually capable natural person over 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/brokerflat-com/eligibility/brokerflat-com-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from BrokerFlat's own page on 2026-11-09.
synthetic: false
tags:
- Fintech
- Cashback
- Foreign Exchange
- Brokerage
- Rebate
---
