---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: These terms are between Base Ledger IP LLC, a Virginia company ("BaseLedger," "we," "us"), and the business that signs up ("you" or "the shop").
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: A card is required at signup.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: BaseLedger IP
provenance_date: '2026-11-09'
provider_name: BaseLedger IP
provider_slug: baseledgerip-com
slug: baseledgerip-com-eligibility
source_date: '2026-11-09'
source_filename: baseledgerip-com-eligibility.yml
source_heading: Eligibility
source_page: https://baseledgerip.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BaseLedger IP\naid: baseledgerip-com\nurl: https://baseledgerip.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: These terms are between Base Ledger IP LLC, a Virginia company (\"BaseLedger,\" \"we,\" \"us\"), and the business\n    that signs up (\"you\" or \"the shop\").\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: A card is required at signup.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/baseledgerip-com/eligibility/baseledgerip-com-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 2 quoted statements, read from BaseLedger IP's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Phone Answering
- HVAC
- Plumbing
- Electrical
- Virginia
---
