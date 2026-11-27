---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: The Website is not intended for or directed at children under the age of 13
    value: '13'
  restricted_uses:
  - summary: Unlawful or prohibited use
    text: As a condition of your use of the Website, you warrant to Provus that you will not use the Website for any purpose that is unlawful or prohibited by these terms, conditions, and notices.
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
name: Provus
provenance_date: '2026-11-10'
provider_name: Provus
provider_slug: provusinc
slug: provusinc-eligibility
source_date: '2026-11-10'
source_filename: provusinc-eligibility.yml
source_heading: Eligibility
source_page: https://provus.ai/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Provus\naid: provusinc\nurl: https://provus.ai/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or prohibited use\n  text: As a condition of your use of the Website, you warrant to Provus that you will not use the Website for any\n    purpose that is unlawful or prohibited by these terms, conditions, and notices.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Website is not intended for or directed at children under the age of\
  \ 13\n"
source_yaml_url: https://artifacts.apis.io/provusinc/eligibility/provusinc-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Provus's own page on 2026-11-10.
synthetic: false
tags:
- Company
- CPQ
- Services Quoting
- Professional Services
- Pricing
- AI Agents
- Sales
- Software-as-a-Service
---
