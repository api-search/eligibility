---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Upstream and the Services are operated from within the United States. You must not access or use the Services from a territory that is embargoed by the United States or from which it is illegal to receive products, services, or software from the United States.
  entity_types:
  - text: The Services are offered and available to users who are 18 years of age or older.
    type: individual
  minimum_age:
    text: The Services are offered and available to users who are 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: Personal, non-commercial purposes
    text: You will only use the Services in accordance with the laws of your jurisdiction for personal, non-commercial purposes.
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
name: Upstream
provenance_date: '2026-11-10'
provider_name: Upstream
provider_slug: upstream
slug: upstream-eligibility
source_date: '2026-11-10'
source_filename: upstream-eligibility.yml
source_heading: Eligibility
source_page: https://upstreamapp.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Upstream\naid: upstream\nurl: https://upstreamapp.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Upstream and the Services are operated from within the United States. You must not access or use the Services\n    from a territory that is embargoed by the United States or from which it is illegal to receive products, services,\n    or software from the United States.\nentity_types:\n- type: individual\n  text: The Services are offered and available to users who are 18 years of age or older.\nrestricted_uses:\n- summary: Personal, non-commercial purposes\n  text: You will\
  \ only use the Services in accordance with the laws of your jurisdiction for personal, non-commercial\n    purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are offered and available to users who are 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/upstream/eligibility/upstream-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Upstream's own page on 2026-11-10.
synthetic: false
tags:
- Company
- DAO
- Web3
- Blockchain
- Governance
- Community
- Ethereum
- No-Code
---
