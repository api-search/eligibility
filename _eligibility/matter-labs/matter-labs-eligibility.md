---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may only access or use the Site or accept the Terms if you are an individual of legal age to form a binding contract
    type: individual
  - text: If you are agreeing to the Terms on behalf of an organization or entity, you represent and warrant that you are authorized to agree to the Terms on that organization's or entity's behalf
    type: business
  minimum_age:
    text: You may only access or use the Site or accept the Terms if you are an individual of legal age to form a binding contract
    value: legal age
  restricted_uses:
  - summary: Personal, non-commercial use only
    text: solely for your own personal, non-commercial use
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
name: Matter Labs
provenance_date: '2026-11-10'
provider_name: Matter Labs
provider_slug: matter-labs
slug: matter-labs-eligibility
source_date: '2026-11-10'
source_filename: matter-labs-eligibility.yml
source_heading: Eligibility
source_page: https://www.zksync.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Matter Labs\naid: matter-labs\nurl: https://www.zksync.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may only access or use the Site or accept the Terms if you are an individual of legal age to form a\n    binding contract\n- type: business\n  text: If you are agreeing to the Terms on behalf of an organization or entity, you represent and warrant that\n    you are authorized to agree to the Terms on that organization's or entity's behalf\nrestricted_uses:\n- summary: Personal, non-commercial use only\n\
  \  text: solely for your own personal, non-commercial use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal age\n  text: You may only access or use the Site or accept the Terms if you are an individual of legal age to form a\n    binding contract\n"
source_yaml_url: https://artifacts.apis.io/matter-labs/eligibility/matter-labs-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Matter Labs's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Blockchain
- Ethereum
- Layer 2
- Zero-Knowledge Proofs
- Rollup
- JSON-RPC
- Web3
- Cryptography
- Scaling
- Real-Time
---
