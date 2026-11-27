---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: WhichPost is made for businesses.
    type: business
  - text: If you use it as a consumer, you keep the protection of the mandatory laws of the country where you live
    type: individual
  minimum_age:
    text: You must be at least 18 and able to enter into a contract.
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
name: whichpost-app
provenance_date: '2026-11-10'
provider_name: whichpost-app
provider_slug: whichpost-app
slug: whichpost-app-eligibility
source_date: '2026-11-10'
source_filename: whichpost-app-eligibility.yml
source_heading: Eligibility
source_page: https://whichpost.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: whichpost-app\naid: whichpost-app\nurl: https://whichpost.app/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: WhichPost is made for businesses.\n- type: individual\n  text: If you use it as a consumer, you keep the protection of the mandatory laws of the country where you live\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 and able to enter into a contract.\n"
source_yaml_url: https://artifacts.apis.io/whichpost-app/eligibility/whichpost-app-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from whichpost-app's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Analytics
- Creator Economy
- Revenue
- Software-as-a-Service
- Marketing
---
