---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Squads makes no representations that the Services are appropriate or available for use in other locations.
  entity_types:
  - text: CUSTOMER IS OF LEGAL AGE TO FORM A BINDING CONTRACT WITH SQUADS
    type: individual
  - text: If Customer is a DAO, references to “Customer” in this Agreement shall include all members of the DAO
    type: other
  minimum_age:
    text: CUSTOMER IS OF LEGAL AGE TO FORM A BINDING CONTRACT WITH SQUADS
    value: null
  restricted_uses:
  - summary: No sanctioned transactions
    text: Customer will not use the Services to facilitate transactions with sanctioned entities or jurisdictions
  - summary: No fraudulent activity
    text: Customer will not use the Services to engage in or facilitate any fraudulent, deceptive, or manipulative activities
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Squads reserves the right, but has no obligation, to request information from Customer to verify Customer’s identity
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Squads
provenance_date: '2026-11-10'
provider_name: Squads
provider_slug: squads
slug: squads-eligibility
source_date: '2026-11-10'
source_filename: squads-eligibility.yml
source_heading: Eligibility
source_page: https://squads.xyz/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Squads\naid: squads\nurl: https://squads.xyz/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Squads makes no representations that the Services are appropriate or available for use in other locations.\nentity_types:\n- type: individual\n  text: CUSTOMER IS OF LEGAL AGE TO FORM A BINDING CONTRACT WITH SQUADS\n- type: other\n  text: If Customer is a DAO, references to “Customer” in this Agreement shall include all members of the DAO\nrestricted_uses:\n- summary: No sanctioned transactions\n  text: Customer will not use the Services to facilitate transactions with\
  \ sanctioned entities or jurisdictions\n- summary: No fraudulent activity\n  text: Customer will not use the Services to engage in or facilitate any fraudulent, deceptive, or manipulative\n    activities\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Squads reserves the right, but has no obligation, to request information from Customer to verify Customer’s\n    identity\nminimum_age:\n  value: null\n  text: CUSTOMER IS OF LEGAL AGE TO FORM A BINDING CONTRACT WITH SQUADS\n"
source_yaml_url: https://artifacts.apis.io/squads/eligibility/squads-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Squads's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Infrastructure
- Blockchain
- Solana
- Multisig
- Smart Accounts
- Stablecoins
- Payments
- Wallets
- Web3
---
