---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: One account per person or legal entity
    type: individual
  - text: If registering on behalf of an organization, you represent that you are authorized to bind that organization to these Terms
    type: business
  minimum_age:
    text: You must be at least 18 years old to use our services
    value: '18'
  restricted_uses:
  - summary: Illegal activity and sanctions evasion
    text: Use our services to facilitate money laundering, sanctions evasion, terrorist financing, or any illegal activity
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
name: BlockchainAnalysis.io
provenance_date: '2026-11-09'
provider_name: BlockchainAnalysis.io
provider_slug: blockchainanalysis-io
slug: blockchainanalysis-io-eligibility
source_date: '2026-11-09'
source_filename: blockchainanalysis-io-eligibility.yml
source_heading: Eligibility
source_page: https://blockchainanalysis.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BlockchainAnalysis.io\naid: blockchainanalysis-io\nurl: https://blockchainanalysis.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: One account per person or legal entity\n- type: business\n  text: If registering on behalf of an organization, you represent that you are authorized to bind that organization\n    to these Terms\nrestricted_uses:\n- summary: Illegal activity and sanctions evasion\n  text: Use our services to facilitate money laundering, sanctions evasion, terrorist financing, or any illegal\n    activity\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use our services\n"
source_yaml_url: https://artifacts.apis.io/blockchainanalysis-io/eligibility/blockchainanalysis-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from BlockchainAnalysis.io's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Compliance
- Blockchain
- AML
- Transaction Monitoring
---
