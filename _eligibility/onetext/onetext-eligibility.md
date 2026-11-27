---
claim_count: 1
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
  - summary: Violations of law, including TCPA and CCPA
    text: including, for the avoidance of doubt, the Telephone Consumer Protection Act and the California Consumer Privacy Act and other similar applicable laws of any jurisdiction.
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
name: OneText
provenance_date: '2026-11-10'
provider_name: OneText
provider_slug: onetext
slug: onetext-eligibility
source_date: '2026-11-10'
source_filename: onetext-eligibility.yml
source_heading: Eligibility
source_page: https://home.onetext.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: OneText\naid: onetext\nurl: https://home.onetext.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Violations of law, including TCPA and CCPA\n  text: including, for the avoidance of doubt, the Telephone Consumer Protection Act and the California Consumer\n    Privacy Act and other similar applicable laws of any jurisdiction.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/onetext/eligibility/onetext-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from OneText's own page on 2026-11-10.
synthetic: false
tags:
- Text to Buy
- E-Commerce
- SMS Marketing
- Conversational Sales
- AI Smart Replies
- Payments
- Cart Recovery
---
