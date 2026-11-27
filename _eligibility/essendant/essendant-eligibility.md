---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Resale and personal consumption
    text: Resellers withdrawing items from stock for personal consumption are responsible for self-assessing use tax in accordance with applicable state law.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: All orders are subject to credit approval by Essendant.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Essendant
provenance_date: '2026-11-09'
provider_name: Essendant
provider_slug: essendant
slug: essendant-eligibility
source_date: '2026-11-09'
source_filename: essendant-eligibility.yml
source_heading: Eligibility
source_page: https://www.essendant.com/essendant-terms-of-sale/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Essendant\naid: essendant\nurl: https://www.essendant.com/essendant-terms-of-sale/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Resale and personal consumption\n  text: Resellers withdrawing items from stock for personal consumption are responsible for self-assessing use tax\n    in accordance with applicable state law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: All orders are subject to credit approval by Essendant.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/essendant/eligibility/essendant-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Essendant's own page on 2026-11-09.
synthetic: false
tags:
- Wholesale
- Distribution
- Supply Chain
- Office Supplies
- Fulfillment
- 3PL
- B2B
- EDI
- E-Commerce
- JanSan
- Food Service
---
