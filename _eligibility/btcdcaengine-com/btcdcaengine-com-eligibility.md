---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Accounts are personal to one individual.
    type: individual
  minimum_age:
    text: You must be at least 18 years old and legally able to enter into a contract.
    value: '18'
  restricted_uses:
  - summary: Unlawful or infringing use
    text: use the Service to break the law, infringe anyone's rights, or present its output to third parties as personalized financial advice.
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
name: BTC DCA Engine
provenance_date: '2026-11-09'
provider_name: BTC DCA Engine
provider_slug: btcdcaengine-com
slug: btcdcaengine-com-eligibility
source_date: '2026-11-09'
source_filename: btcdcaengine-com-eligibility.yml
source_heading: Eligibility
source_page: https://btcdcaengine.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BTC DCA Engine\naid: btcdcaengine-com\nurl: https://btcdcaengine.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Accounts are personal to one individual.\nrestricted_uses:\n- summary: Unlawful or infringing use\n  text: use the Service to break the law, infringe anyone's rights, or present its output to third parties as personalized\n    financial advice.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and legally\
  \ able to enter into a contract.\n"
source_yaml_url: https://artifacts.apis.io/btcdcaengine-com/eligibility/btcdcaengine-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from BTC DCA Engine's own page on 2026-11-09.
synthetic: false
tags:
- Bitcoin
- DCA
- Calculator
- Finance
- Cryptocurrency
---
