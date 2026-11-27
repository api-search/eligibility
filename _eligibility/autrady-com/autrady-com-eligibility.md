---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 and able to enter into a contract. An account is for one person.
    type: individual
  minimum_age:
    text: You must be at least 18 and able to enter into a contract.
    value: '18'
  restricted_uses:
  - summary: Track claim restrictions
    text: Don't call it verified profitable, certified or guaranteed, and don't alter the badge.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You sign in with a Google account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Autrady
provenance_date: '2026-11-09'
provider_name: Autrady
provider_slug: autrady-com
slug: autrady-com-eligibility
source_date: '2026-11-09'
source_filename: autrady-com-eligibility.yml
source_heading: Eligibility
source_page: https://autrady.com/Home/Terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Autrady\naid: autrady-com\nurl: https://autrady.com/Home/Terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 and able to enter into a contract. An account is for one person.\nrestricted_uses:\n- summary: Track claim restrictions\n  text: Don't call it verified profitable, certified or guaranteed, and don't alter the badge.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You sign in with a Google account.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 and able to\
  \ enter into a contract.\n"
source_yaml_url: https://artifacts.apis.io/autrady-com/eligibility/autrady-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Autrady's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Trading
- Analytics
- Research
- Software
---
