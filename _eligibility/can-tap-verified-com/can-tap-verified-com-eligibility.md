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
  - summary: Review gating and incentives
    text: You must not use CAN-TAP to gate reviews, pressure customers, offer incentives for positive reviews, or violate Google Business Profile policies or applicable Canadian laws.
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
name: CAN-TAP Verified
provenance_date: '2026-11-09'
provider_name: CAN-TAP Verified
provider_slug: can-tap-verified-com
slug: can-tap-verified-com-eligibility
source_date: '2026-11-09'
source_filename: can-tap-verified-com-eligibility.yml
source_heading: Eligibility
source_page: https://can-tap-verified.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CAN-TAP Verified\naid: can-tap-verified-com\nurl: https://can-tap-verified.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Review gating and incentives\n  text: You must not use CAN-TAP to gate reviews, pressure customers, offer incentives for positive reviews, or\n    violate Google Business Profile policies or applicable Canadian laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/can-tap-verified-com/eligibility/can-tap-verified-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from CAN-TAP Verified's own page on 2026-11-09.
synthetic: false
tags:
- Canadian
- Business
- Verification
- NFC
- Reputation
---
