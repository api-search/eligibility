---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are available only to individuals who can form legally binding contracts under applicable law.
    type: individual
  - text: it is our intent that the Services be used only by non-profit entities or by for-profit entities raising money on behalf of and for the exclusive benefit of a non-profit entity.
    type: nonprofit
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Non-profit fundraising only
    text: ReadySetAuction’s role is to facilitate non-profit fundraising events.
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
name: ReadySetAuction
provenance_date: '2026-11-10'
provider_name: ReadySetAuction
provider_slug: readysetauction
slug: readysetauction-eligibility
source_date: '2026-11-10'
source_filename: readysetauction-eligibility.yml
source_heading: Eligibility
source_page: https://www.readysetauction.com/policies/tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ReadySetAuction\naid: readysetauction\nurl: https://www.readysetauction.com/policies/tos/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Services are available only to individuals who can form legally binding contracts under applicable law.\n- type: nonprofit\n  text: it is our intent that the Services be used only by non-profit entities or by for-profit entities raising\n    money on behalf of and for the exclusive benefit of a non-profit entity.\nrestricted_uses:\n- summary: Non-profit fundraising only\n  text: ReadySetAuction’s\
  \ role is to facilitate non-profit fundraising events.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/readysetauction/eligibility/readysetauction-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from ReadySetAuction's own page on 2026-11-10.
synthetic: false
tags:
- Auction Software
- Event Management
- Mobile Bidding
- Online Auction
- Guest Management
---
