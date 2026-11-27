---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The App is for domestic and private use.
    type: individual
  minimum_age:
    text: You must be 18 or over to accept these terms and use the App. Accounts for those under 18 must be created and supervised by a parent or guardian over the age of 18.
    value: '18'
  restricted_uses:
  - summary: Commercial or resale use
    text: If you use the App for any commercial, business or resale purpose we will have no liability to you for any loss of profit, loss of business, business interruption, or loss of business opportunity.
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
name: Tooth Fairy
provenance_date: '2026-11-10'
provider_name: Tooth Fairy
provider_slug: tooth-fairy
slug: tooth-fairy-eligibility
source_date: '2026-11-10'
source_filename: tooth-fairy-eligibility.yml
source_heading: Eligibility
source_page: https://www.toothfairyapp.co.uk/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tooth Fairy\naid: tooth-fairy\nurl: https://www.toothfairyapp.co.uk/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The App is for domestic and private use.\nrestricted_uses:\n- summary: Commercial or resale use\n  text: If you use the App for any commercial, business or resale purpose we will have no liability to you for any\n    loss of profit, loss of business, business interruption, or loss of business opportunity.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n\
  \  text: You must be 18 or over to accept these terms and use the App. Accounts for those under 18 must be created\n    and supervised by a parent or guardian over the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/tooth-fairy/eligibility/tooth-fairy-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Tooth Fairy's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Dental
- Telehealth
- Healthcare
- Orthodontics
- Mobile App
- United Kingdom
---
