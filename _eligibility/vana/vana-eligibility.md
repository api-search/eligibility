---
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - US
    - KP
    - CU
    - IR
    - SY
    served: []
    text: You are not (a) a United States citizen; (b) a United States residents; You are neither a citizen of nor domiciled within any nation or region subjected to comprehensive sanctions, including, but not limited to, Cuba, Democratic People's Republic of Korea, the Crimea, Donetsk, Luhansk regions, Iran, or Syria.
  entity_types:
  - text: You are at least eighteen (18) years of age and possess the legal capacity to enter into a binding agreement with us.
    type: individual
  minimum_age:
    text: You are at least eighteen (18) years of age and possess the legal capacity to enter into a binding agreement with us.
    value: '18'
  restricted_uses:
  - summary: No sanctions evasion
    text: (h) attempt to bypass sanctions or export controls imposed on you or your location
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: The Foundation reserves the right, in its sole discretion, to determine the eligibility of users for the Services. We may require you to provide information and/or documentation to verify or confirm your eligibility, including on a periodic or ongoing basis.
excluded_countries:
- US
- KP
- CU
- IR
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Vana
provenance_date: '2026-11-10'
provider_name: Vana
provider_slug: vana
slug: vana-eligibility
source_date: '2026-11-10'
source_filename: vana-eligibility.yml
source_heading: Eligibility
source_page: https://vana.org/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vana\naid: vana\nurl: https://vana.org/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - US\n  - KP\n  - CU\n  - IR\n  - SY\n  text: You are not (a) a United States citizen; (b) a United States residents; You are neither a citizen of nor\n    domiciled within any nation or region subjected to comprehensive sanctions, including, but not limited to, Cuba,\n    Democratic People's Republic of Korea, the Crimea, Donetsk, Luhansk regions, Iran, or Syria.\nentity_types:\n- type: individual\n  text: You are at least eighteen (18) years of age and possess the legal capacity to enter into a\
  \ binding agreement\n    with us.\nrestricted_uses:\n- summary: No sanctions evasion\n  text: (h) attempt to bypass sanctions or export controls imposed on you or your location\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: The Foundation reserves the right, in its sole discretion, to determine the eligibility of users for the\n    Services. We may require you to provide information and/or documentation to verify or confirm your eligibility,\n    including on a periodic or ongoing basis.\nminimum_age:\n  value: '18'\n  text: You are at least eighteen (18) years of age and possess the legal capacity to enter into a binding agreement\n    with us.\n"
source_yaml_url: https://artifacts.apis.io/vana/eligibility/vana-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Vana's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Crypto Ai
- Data Portability
- Personal Data
- Data Sovereignty
- Blockchain
- Web3
- Agents
- Artificial Intelligence
---
