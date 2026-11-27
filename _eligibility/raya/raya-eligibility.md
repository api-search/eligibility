---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Organizations, companies, and/or businesses may not use the Service for any purpose except with Raya’s express consent, which consent may be withheld in our sole discretion.
    type: business
  minimum_age:
    text: You must be at least 18 years of age to use the Service.
    value: '18'
  restricted_uses:
  - summary: Personal use only
    text: The Service is for personal use only.
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
name: Raya
provenance_date: '2026-11-10'
provider_name: Raya
provider_slug: raya
slug: raya-eligibility
source_date: '2026-11-10'
source_filename: raya-eligibility.yml
source_heading: Eligibility
source_page: https://www.rayatheapp.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Raya\naid: raya\nurl: https://www.rayatheapp.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Organizations, companies, and/or businesses may not use the Service for any purpose except with Raya’s express\n    consent, which consent may be withheld in our sole discretion.\nrestricted_uses:\n- summary: Personal use only\n  text: The Service is for personal use only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use\
  \ the Service.\n"
source_yaml_url: https://artifacts.apis.io/raya/eligibility/raya-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Raya's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Social Network
- Dating
- Community
- Membership
- Mobile
- iOS
- Subscription
- Los Angeles
---
