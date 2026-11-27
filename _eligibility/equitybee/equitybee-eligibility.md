---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If You are entering into these Terms on behalf of a company or another legal entity, You represent that You have the authority to bind such entity
    type: business
  minimum_age:
    text: If You are under 18 years old, please do not use or attempt to register to use the Services.
    value: '18'
  restricted_uses:
  - summary: Non-commercial personal use only
    text: You may access and use the Services through the Platform solely for the purpose of Your own personal noncommercial use.
  - summary: Accredited investors only (website)
    text: This website is intended solely for accredited investors.
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
name: EquityBee
provenance_date: '2026-11-09'
provider_name: EquityBee
provider_slug: equitybee
slug: equitybee-eligibility
source_date: '2026-11-09'
source_filename: equitybee-eligibility.yml
source_heading: Eligibility
source_page: https://equitybee.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: EquityBee\naid: equitybee\nurl: https://equitybee.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If You are entering into these Terms on behalf of a company or another legal entity, You represent that\n    You have the authority to bind such entity\nrestricted_uses:\n- summary: Non-commercial personal use only\n  text: You may access and use the Services through the Platform solely for the purpose of Your own personal noncommercial\n    use.\n- summary: Accredited investors only (website)\n  text: This website is intended\
  \ solely for accredited investors.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: If You are under 18 years old, please do not use or attempt to register to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/equitybee/eligibility/equitybee-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from EquityBee's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Financial Services
- Equity
- Stock Options
- Marketplace
- Investing
- Startups
- Pre-IPO
---
