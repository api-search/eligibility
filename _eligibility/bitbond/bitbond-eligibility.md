---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If a Customer is a consumer and its habitual residence is in a member state of the European Union, German law shall also apply
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal or unauthorized use
    text: If there is any suspicion of illegal or punishable actions, Bitbond may and, as necessary, must audit the activities of the user
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: The Services may require you to create an account, and enter a valid means of payment via a Web3 wallet.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bitbond
provenance_date: '2026-11-09'
provider_name: Bitbond
provider_slug: bitbond
slug: bitbond-eligibility
source_date: '2026-11-09'
source_filename: bitbond-eligibility.yml
source_heading: Eligibility
source_page: https://tokentool.bitbond.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bitbond\naid: bitbond\nurl: https://tokentool.bitbond.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If a Customer is a consumer and its habitual residence is in a member state of the European Union, German\n    law shall also apply\nrestricted_uses:\n- summary: Illegal or unauthorized use\n  text: If there is any suspicion of illegal or punishable actions, Bitbond may and, as necessary, must audit the\n    activities of the user\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: The Services may\
  \ require you to create an account, and enter a valid means of payment via a Web3 wallet.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bitbond/eligibility/bitbond-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Bitbond's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Tokenization
- Blockchain
- Digital Assets
- Smart Contracts
- Web3
- Securities
- Payments
- MCP
---
