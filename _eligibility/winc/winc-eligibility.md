---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: 'Member Credits: the order recipient must be a resident of the United States in a state where it is legal to directly ship wine.'
  entity_types:
  - text: The Sites are directed to adults aged 21 or older and you must be at least 21 years of age to make a purchase through the Sites
    type: individual
  minimum_age:
    text: you represent and warrant that you are at least twenty-one (21) years of age.
    value: '21'
  restricted_uses:
  - summary: No purchases for under-21s
    text: nor may you do any of the foregoing activities for the benefit, or on behalf, of any person under the age of 21.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: a valid government-issued ID will be required upon delivery
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Winc
provenance_date: '2026-11-10'
provider_name: Winc
provider_slug: winc
slug: winc-eligibility
source_date: '2026-11-10'
source_filename: winc-eligibility.yml
source_heading: Eligibility
source_page: https://www.winc.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Winc\naid: winc\nurl: https://www.winc.com/policies/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: 'Member Credits: the order recipient must be a resident of the United States in a state where it is legal\n    to directly ship wine.'\nentity_types:\n- type: individual\n  text: The Sites are directed to adults aged 21 or older and you must be at least 21 years of age to make a purchase\n    through the Sites\nrestricted_uses:\n- summary: No purchases for under-21s\n  text: nor may you do any of the foregoing activities for the benefit, or on behalf, of any person\
  \ under the age\n    of 21.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: a valid government-issued ID will be required upon delivery\nminimum_age:\n  value: '21'\n  text: you represent and warrant that you are at least twenty-one (21) years of age.\n"
source_yaml_url: https://artifacts.apis.io/winc/eligibility/winc-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Winc's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Wine
- E-Commerce
- Retail
- Subscription
- Agentic Commerce
- MCP
- Shopify
- Universal Commerce Protocol
---
