---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accessing or using the Service on behalf of your company, you represent that you are authorized to accept this Agreement on behalf of your company
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal or harmful use
    text: Customer shall not use the Service in connection with any Application or business that is prohibited by Laws (e.g., illegal drug sales or money laundering), that violates the rights of others, or that may be harmful to others.
  - summary: Sanctioned parties and export
    text: Customer represents and warrants that it is not designated on any list of prohibited or restricted parties
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
name: Chain
provenance_date: '2026-11-09'
provider_name: Chain
provider_slug: chain
slug: chain-eligibility
source_date: '2026-11-09'
source_filename: chain-eligibility.yml
source_heading: Eligibility
source_page: https://chain.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Chain\naid: chain\nurl: https://chain.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accessing or using the Service on behalf of your company, you represent that you are authorized\n    to accept this Agreement on behalf of your company\nrestricted_uses:\n- summary: Illegal or harmful use\n  text: Customer shall not use the Service in connection with any Application or business that is prohibited by\n    Laws (e.g., illegal drug sales or money laundering), that violates the rights of others, or that may be harmful\n\
  \    to others.\n- summary: Sanctioned parties and export\n  text: Customer represents and warrants that it is not designated on any list of prohibited or restricted parties\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/chain/eligibility/chain-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Chain's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Stablecoins
- Cryptocurrency
- Blockchain
- Financial Services
- Wallets
- Cards
- Cross-Border Payments
---
