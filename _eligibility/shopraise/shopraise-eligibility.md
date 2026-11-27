---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We provide the Service for use only by persons located in the United States.
  entity_types:
  - text: ShopRaise provides an online fundraising platform and tools to organizations (including but not limited to non-profit organizations)
    type: nonprofit
  minimum_age:
    text: You are a U.S. citizen and 18 years of age or older, or you have received parental consent and are acting under parental supervision if you are under 18.
    value: '18'
  restricted_uses:
  - summary: Political campaigning
    text: Is substantially or primarily focused on campaigning for, participating or intervening in, supporting or backing, whether, directly or indirectly, any political campaign
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
name: ShopRaise
provenance_date: '2026-11-10'
provider_name: ShopRaise
provider_slug: shopraise
slug: shopraise-eligibility
source_date: '2026-11-10'
source_filename: shopraise-eligibility.yml
source_heading: Eligibility
source_page: https://shopraise.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ShopRaise\naid: shopraise\nurl: https://shopraise.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We provide the Service for use only by persons located in the United States.\nentity_types:\n- type: nonprofit\n  text: ShopRaise provides an online fundraising platform and tools to organizations (including but not limited\n    to non-profit organizations)\nrestricted_uses:\n- summary: Political campaigning\n  text: Is substantially or primarily focused on campaigning for, participating or intervening in, supporting or\n    backing, whether, directly or indirectly, any\
  \ political campaign\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are a U.S. citizen and 18 years of age or older, or you have received parental consent and are acting\n    under parental supervision if you are under 18.\n"
source_yaml_url: https://artifacts.apis.io/shopraise/eligibility/shopraise-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from ShopRaise's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fundraising
- E-Commerce
- Non-Profit
- Software-as-a-Service
---
