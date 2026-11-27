---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Payall makes no representation that Materials or other content on the Site are appropriate or available for use outside the United States, its territories, possessions and protectorates.
  entity_types:
  - text: You represent that you are at least eighteen (18) years of age.
    type: individual
  minimum_age:
    text: You represent that you are at least eighteen (18) years of age.
    value: '18'
  restricted_uses:
  - summary: Unlawful use
    text: You may only use this Site and its contents for lawful purposes and in accordance with applicable law
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
name: Payall
provenance_date: '2026-11-10'
provider_name: Payall
provider_slug: payall
slug: payall-eligibility
source_date: '2026-11-10'
source_filename: payall-eligibility.yml
source_heading: Eligibility
source_page: https://payall.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Payall\naid: payall\nurl: https://payall.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Payall makes no representation that Materials or other content on the Site are appropriate or available\n    for use outside the United States, its territories, possessions and protectorates.\nentity_types:\n- type: individual\n  text: You represent that you are at least eighteen (18) years of age.\nrestricted_uses:\n- summary: Unlawful use\n  text: You may only use this Site and its contents for lawful purposes and in accordance with applicable law\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent that you are at least eighteen (18) years of age.\n"
source_yaml_url: https://artifacts.apis.io/payall/eligibility/payall-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Payall's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payments
- Cross-Border Payments
- Banking Infrastructure
- Fintech
- Compliance
- Financial Services
---
