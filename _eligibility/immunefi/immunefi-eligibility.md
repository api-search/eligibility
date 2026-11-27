---
claim_count: 3
description: ''
doc:
  countries:
    excluded:
    - BY
    - CU
    - CD
    - IR
    - KP
    - LR
    - MM
    - SD
    - SY
    - ZW
    served: []
    text: they are a citizen of or otherwise accessing the Website from countries subject to sanctions by the United States Office of Foreign Asset Control (“ OFAC ”), including but not limited to the nations of Belarus, Burma (Myanmar), Cuba, Democratic Republic of Congo, Iran, Liberia, North Korea, Sudan, Syria, and Zimbabwe
  minimum_age:
    text: The Website is offered and available to users who are eighteen (18) years of age or older.
    value: '18'
  restricted_uses:
  - summary: Prohibited jurisdictions
    text: If they are a citizen of or otherwise accessing the Website from countries subject to sanctions by the United States Office of Foreign Asset Control
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- BY
- CU
- CD
- IR
- KP
- LR
- MM
- SD
- SY
- ZW
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Immunefi
provenance_date: '2026-11-09'
provider_name: Immunefi
provider_slug: immunefi
slug: immunefi-eligibility
source_date: '2026-11-09'
source_filename: immunefi-eligibility.yml
source_heading: Eligibility
source_page: https://immunefi.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Immunefi\naid: immunefi\nurl: https://immunefi.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - BY\n  - CU\n  - CD\n  - IR\n  - KP\n  - LR\n  - MM\n  - SD\n  - SY\n  - ZW\n  text: they are a citizen of or otherwise accessing the Website from countries subject to sanctions by the United\n    States Office of Foreign Asset Control (“ OFAC ”), including but not limited to the nations of Belarus, Burma\n    (Myanmar), Cuba, Democratic Republic of Congo, Iran, Liberia, North Korea, Sudan, Syria, and Zimbabwe\nentity_types: []\nrestricted_uses:\n- summary: Prohibited jurisdictions\n\
  \  text: If they are a citizen of or otherwise accessing the Website from countries subject to sanctions by the United\n    States Office of Foreign Asset Control\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Website is offered and available to users who are eighteen (18) years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/immunefi/eligibility/immunefi-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Immunefi's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Bug Bounty
- Vulnerability Disclosure
- Web3
- Blockchain
- Smart Contracts
- Application Security
- Cryptocurrency
- Crowdsourced Security
---
