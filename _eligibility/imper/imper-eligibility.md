---
claim_count: 1
description: ''
doc:
  countries:
    excluded:
    - CU
    - LB
    - IR
    - SY
    - KP
    served: []
    text: Customer represents that it is not incorporated under the laws of, operating from, or ordinarily resident in a country or territory subject to comprehensive U.S. or Israeli economic or trade sanctions (currently, Cuba, Lebanon, Iran, Syria, North Korea, or the Crimea region of Ukraine)
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- LB
- IR
- SY
- KP
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Imper
provenance_date: '2026-11-09'
provider_name: Imper
provider_slug: imper
slug: imper-eligibility
source_date: '2026-11-09'
source_filename: imper-eligibility.yml
source_heading: Eligibility
source_page: https://imper.ai/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Imper\naid: imper\nurl: https://imper.ai/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - LB\n  - IR\n  - SY\n  - KP\n  text: Customer represents that it is not incorporated under the laws of, operating from, or ordinarily resident\n    in a country or territory subject to comprehensive U.S. or Israeli economic or trade sanctions (currently, Cuba,\n    Lebanon, Iran, Syria, North Korea, or the Crimea region of Ukraine)\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/imper/eligibility/imper-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from Imper's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cybersecurity
- Identity Verification
- Impersonation Detection
- Social Engineering Defense
- Workforce Security
- Fraud Prevention
- Help Desk Security
---
