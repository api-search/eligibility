---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Insurance excluded for certain activities
    text: 'access to insurance is not permitted for any company that engages in any of the following activities: sale of weapons, drugs, sale of illegal substances and products, communication and dissemination of information or images of an erotic or pornographic nature, websites of a religious, political or ideological nature, gambling and betting activities, social networks, activities related to cryptocurrencies, airports, stock markets.'
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
name: Stoik
provenance_date: '2026-11-10'
provider_name: Stoik
provider_slug: stoik
slug: stoik-eligibility
source_date: '2026-11-10'
source_filename: stoik-eligibility.yml
source_heading: Eligibility
source_page: https://www.stoik.com/en-us/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Stoik\naid: stoik\nurl: https://www.stoik.com/en-us/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Insurance excluded for certain activities\n  text: 'access to insurance is not permitted for any company that engages in any of the following activities: sale\n    of weapons, drugs, sale of illegal substances and products, communication and dissemination of information or\n    images of an erotic or pornographic nature, websites of a religious, political or ideological nature, gambling\n    and betting activities, social networks,\
  \ activities related to cryptocurrencies, airports, stock markets.'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/stoik/eligibility/stoik-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Stoik's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cyber Insurance
- Cybersecurity
- Insurtech
- Managed Detection and Response
- Email Security
- Phishing Simulation
- Vulnerability Scanning
- Incident Response
- Europe
---
