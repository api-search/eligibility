---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: EASE offers its software services for a fee to brokers and some employers.
    type: business
  minimum_age:
    text: YOU REPRESENT THAT YOU ARE AT LEAST 18 YEARS OLD AND THAT YOU ARE LEGALLY ABLE TO ENTER INTO THIS USER AGREEMENT.
    value: '18'
  restricted_uses:
  - summary: Broker of record accounts only
    text: If you are the broker, unless otherwise specified, usage is limited to accounts where the user is the broker of record.
  - summary: No subscription sharing
    text: You are prohibited from sharing subscriptions.
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
name: EaseCentral
provenance_date: '2026-11-09'
provider_name: EaseCentral
provider_slug: easecentral
slug: easecentral-eligibility
source_date: '2026-11-09'
source_filename: easecentral-eligibility.yml
source_heading: Eligibility
source_page: https://www.ease.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: EaseCentral\naid: easecentral\nurl: https://www.ease.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: EASE offers its software services for a fee to brokers and some employers.\nrestricted_uses:\n- summary: Broker of record accounts only\n  text: If you are the broker, unless otherwise specified, usage is limited to accounts where the user is the broker\n    of record.\n- summary: No subscription sharing\n  text: You are prohibited from sharing subscriptions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '18'\n  text: YOU REPRESENT THAT YOU ARE AT LEAST 18 YEARS OLD AND THAT YOU ARE LEGALLY ABLE TO ENTER INTO THIS USER AGREEMENT.\n"
source_yaml_url: https://artifacts.apis.io/easecentral/eligibility/easecentral-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from EaseCentral's own page on 2026-11-09.
synthetic: false
tags:
- Benefits
- Human Resources
- Insurance
- Software-as-a-Service
- Brokerage
---
