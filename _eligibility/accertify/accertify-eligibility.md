---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Password-protected areas
    text: Access to and use of password protected and secure areas of this site and the Content provided there is restricted to authorized users only.
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
name: Accertify
provenance_date: '2026-11-09'
provider_name: Accertify
provider_slug: accertify
slug: accertify-eligibility
source_date: '2026-11-09'
source_filename: accertify-eligibility.yml
source_heading: Eligibility
source_page: https://www.accertify.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Accertify\naid: accertify\nurl: https://www.accertify.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Password-protected areas\n  text: Access to and use of password protected and secure areas of this site and the Content provided there is\n    restricted to authorized users only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/accertify/eligibility/accertify-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Accertify's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fraud Prevention
- Payments
- Risk Management
- Fintech
---
