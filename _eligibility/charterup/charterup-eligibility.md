---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: These Terms govern your access or use, from within the United States and its territories and possessions, of the applications, websites, content, products, and services
  entity_types:
  - text: the Services are made available solely for your personal, noncommercial use
    type: individual
  minimum_age:
    text: You must be at least 18 years of age, or the age of legal majority in your jurisdiction (if different than 18), to obtain an Account
    value: '18'
  restricted_uses:
  - summary: Unlawful or hazardous transport
    text: no transport of unlawful or hazardous materials
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In certain instances you may be asked to provide proof of identity or other method of identity verification to access or use the Services
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Charterup
provenance_date: '2026-11-09'
provider_name: Charterup
provider_slug: charterup
slug: charterup-eligibility
source_date: '2026-11-09'
source_filename: charterup-eligibility.yml
source_heading: Eligibility
source_page: https://www.charterup.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Charterup\naid: charterup\nurl: https://www.charterup.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: These Terms govern your access or use, from within the United States and its territories and possessions,\n    of the applications, websites, content, products, and services\nentity_types:\n- type: individual\n  text: the Services are made available solely for your personal, noncommercial use\nrestricted_uses:\n- summary: Unlawful or hazardous transport\n  text: no transport of unlawful or hazardous materials\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: In certain instances you may be asked to provide proof of identity or other method of identity verification\n    to access or use the Services\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age, or the age of legal majority in your jurisdiction (if different than\n    18), to obtain an Account\n"
source_yaml_url: https://artifacts.apis.io/charterup/eligibility/charterup-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Charterup's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Transportation
- On-Demand
- Bus
- Software-as-a-Service
---
