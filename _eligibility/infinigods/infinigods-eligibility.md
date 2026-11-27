---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you are not located in a country that is subject to a U.S. Government embargo
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Money laundering and illicit finance
    text: Use the Service for money laundering, terrorist financing, or other illicit finance
  - summary: Sanctioned countries or persons
    text: Use the Service from a country sanctioned by the government of the United States or to facilitate transactions involving individuals sanctioned by the government of the United States or located in sanctioned countries
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: InfiniGods may require you to provide additional information and documents in certain circumstances, such as at the request of any government authority
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: InfiniGods
provenance_date: '2026-11-09'
provider_name: InfiniGods
provider_slug: infinigods
slug: infinigods-eligibility
source_date: '2026-11-09'
source_filename: infinigods-eligibility.yml
source_heading: Eligibility
source_page: https://www.infinigods.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: InfiniGods\naid: infinigods\nurl: https://www.infinigods.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: you are not located in a country that is subject to a U.S. Government embargo\nentity_types: []\nrestricted_uses:\n- summary: Money laundering and illicit finance\n  text: Use the Service for money laundering, terrorist financing, or other illicit finance\n- summary: Sanctioned countries or persons\n  text: Use the Service from a country sanctioned by the government of the United States or to facilitate transactions\n    involving individuals sanctioned by the\
  \ government of the United States or located in sanctioned countries\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: InfiniGods may require you to provide additional information and documents in certain circumstances, such\n    as at the request of any government authority\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/infinigods/eligibility/infinigods-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 4 quoted statements, read from InfiniGods's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cryptocurrency
- Web3
- Blockchain Games
- Gaming
- Gaming Studio
- NFT
- Mobile Games
---
