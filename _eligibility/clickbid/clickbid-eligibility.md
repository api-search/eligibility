---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Users must reside in a jurisdiction where the Service is available; availability varies by country and is determined by us and our partners.
  entity_types:
  - text: 'To use the Service you must: (a) be at least 18 years old'
    type: individual
  minimum_age:
    text: be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Personal, non-commercial use only
    text: use the Service only for personal, non-commercial purposes
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We or our redemption providers may require additional information — including identity, payment, or tax information — before fulfilling a redemption
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ClickBid
provenance_date: '2026-11-09'
provider_name: ClickBid
provider_slug: clickbid
slug: clickbid-eligibility
source_date: '2026-11-09'
source_filename: clickbid-eligibility.yml
source_heading: Eligibility
source_page: https://clickbid.io/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ClickBid\naid: clickbid\nurl: https://clickbid.io/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Users must reside in a jurisdiction where the Service is available; availability varies by country and is\n    determined by us and our partners.\nentity_types:\n- type: individual\n  text: 'To use the Service you must: (a) be at least 18 years old'\nrestricted_uses:\n- summary: Personal, non-commercial use only\n  text: use the Service only for personal, non-commercial purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We or our redemption providers\
  \ may require additional information — including identity, payment, or tax\n    information — before fulfilling a redemption\nminimum_age:\n  value: '18'\n  text: be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/clickbid/eligibility/clickbid-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from ClickBid's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Mobile
- Gaming
- Payments
- Wallets
---
