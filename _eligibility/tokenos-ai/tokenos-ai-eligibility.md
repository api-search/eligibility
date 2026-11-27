---
claim_count: 6
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    served: []
    text: TokenOS prohibits, and technically blocks, all access to and use of the Platform from, in, or for the benefit of any Restricted Jurisdiction, including Iran, North Korea, Cuba, Syria, and the Crimea, Donetsk and Luhansk regions of Ukraine.
  entity_types:
  - text: You must be at least eighteen (18) years of age (or the age of majority in your jurisdiction, if higher) and have the legal capacity to enter into a binding contract.
    type: individual
  - text: If you access the Platform on behalf of a company, partnership, trust or other legal entity, you represent and warrant that you are duly authorized to bind that entity to these Terms
    type: business
  minimum_age:
    text: You must be at least eighteen (18) years of age (or the age of majority in your jurisdiction, if higher)
    value: '18'
  restricted_uses:
  - summary: Prohibited Part 744 EAR end uses
    text: (ii) use, or permit the use of, any compute capacity for any end use prohibited by Part 744 of the EAR
  verification:
    approval_required: true
    kyb: true
    kyc: true
    text: Entities are never approved automatically; every entity application is decided by a named TokenOS compliance reviewer.
excluded_countries:
- CU
- IR
- KP
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: tokenos-ai
provenance_date: '2026-11-10'
provider_name: tokenos-ai
provider_slug: tokenos-ai
slug: tokenos-ai-eligibility
source_date: '2026-11-10'
source_filename: tokenos-ai-eligibility.yml
source_heading: Eligibility
source_page: https://tokenos.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: tokenos-ai\naid: tokenos-ai\nurl: https://tokenos.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: TokenOS prohibits, and technically blocks, all access to and use of the Platform from, in, or for the benefit\n    of any Restricted Jurisdiction, including Iran, North Korea, Cuba, Syria, and the Crimea, Donetsk and Luhansk\n    regions of Ukraine.\nentity_types:\n- type: individual\n  text: You must be at least eighteen (18) years of age (or the age of majority in your jurisdiction, if higher)\n    and have the legal capacity\
  \ to enter into a binding contract.\n- type: business\n  text: If you access the Platform on behalf of a company, partnership, trust or other legal entity, you represent\n    and warrant that you are duly authorized to bind that entity to these Terms\nrestricted_uses:\n- summary: Prohibited Part 744 EAR end uses\n  text: (ii) use, or permit the use of, any compute capacity for any end use prohibited by Part 744 of the EAR\nverification:\n  kyc: true\n  kyb: true\n  approval_required: true\n  text: Entities are never approved automatically; every entity application is decided by a named TokenOS compliance\n    reviewer.\nminimum_age:\n  value: '18'\n  text: You must be at least eighteen (18) years of age (or the age of majority in your jurisdiction, if higher)\n"
source_yaml_url: https://artifacts.apis.io/tokenos-ai/eligibility/tokenos-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from tokenos-ai's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Web3
- Platform
- Tokenization
- Decentralized
---
