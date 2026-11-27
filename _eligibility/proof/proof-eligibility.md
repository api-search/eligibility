---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By agreeing to these Terms, you hereby certify that you are at least 18 years of age.
    type: individual
  minimum_age:
    text: By agreeing to these Terms, you hereby certify that you are at least 18 years of age.
    value: '18'
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
name: PROOF
provenance_date: '2026-11-10'
provider_name: PROOF
provider_slug: proof
slug: proof-eligibility
source_date: '2026-11-10'
source_filename: proof-eligibility.yml
source_heading: Eligibility
source_page: https://proof.xyz/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PROOF\naid: proof\nurl: https://proof.xyz/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By agreeing to these Terms, you hereby certify that you are at least 18 years of age.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: By agreeing to these Terms, you hereby certify that you are at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/proof/eligibility/proof-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from PROOF's own page on 2026-11-10.
synthetic: false
tags:
- Company
- NFT
- Digital Art
- Web3
- Collectibles
- Blockchain
- Community
- Ethereum
---
