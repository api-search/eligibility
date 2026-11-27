---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You can share offers if you are 18 or older.
    type: individual
  minimum_age:
    text: You can share offers if you are 18 or older.
    value: '18'
  restricted_uses:
  - summary: No weapons, alcohol, tobacco or gambling posts
    text: No weapons, alcohol, tobacco or gambling in posts with your link.
  - summary: Purchases for resale excluded
    text: Purchases for resale or on behalf of others don't count.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To get paid you sign up with your email, name, country and payout account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Endorso
provenance_date: '2026-11-09'
provider_name: Endorso
provider_slug: endorso-com
slug: endorso-com-eligibility
source_date: '2026-11-09'
source_filename: endorso-com-eligibility.yml
source_heading: Eligibility
source_page: https://endorso.com/en/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Endorso\naid: endorso-com\nurl: https://endorso.com/en/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You can share offers if you are 18 or older.\nrestricted_uses:\n- summary: No weapons, alcohol, tobacco or gambling posts\n  text: No weapons, alcohol, tobacco or gambling in posts with your link.\n- summary: Purchases for resale excluded\n  text: Purchases for resale or on behalf of others don't count.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To get paid you sign up with your email, name,\
  \ country and payout account.\nminimum_age:\n  value: '18'\n  text: You can share offers if you are 18 or older.\n"
source_yaml_url: https://artifacts.apis.io/endorso-com/eligibility/endorso-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Endorso's own page on 2026-11-09.
synthetic: false
tags:
- Affiliates
- E-Commerce
- Marketing
- Commissions
- Platform
---
