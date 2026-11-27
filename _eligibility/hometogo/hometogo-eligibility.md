---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The place of execution and the court of jurisdiction for all disputes arising from or related to this contract with traders, legal entities under public law or public bodies is Berlin.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No commercial use
    text: A commercial usage of Our Website is explicitly prohibited.
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
name: HomeToGo
provenance_date: '2026-11-09'
provider_name: HomeToGo
provider_slug: hometogo
slug: hometogo-eligibility
source_date: '2026-11-09'
source_filename: hometogo-eligibility.yml
source_heading: Eligibility
source_page: https://www.hometogo.com/legal/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HomeToGo\naid: hometogo\nurl: https://www.hometogo.com/legal/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The place of execution and the court of jurisdiction for all disputes arising from or related to this contract\n    with traders, legal entities under public law or public bodies is Berlin.\nrestricted_uses:\n- summary: No commercial use\n  text: A commercial usage of Our Website is explicitly prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/hometogo/eligibility/hometogo-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from HomeToGo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Travel
- Vacation Rentals
- Marketplace
- Metasearch
- Hospitality
- Partner API
---
