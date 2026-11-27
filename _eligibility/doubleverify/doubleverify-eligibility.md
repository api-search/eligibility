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
  - summary: Unlawful or prohibited use
    text: You are strictly prohibited from using the Websites for any purpose that is considered unlawful or prohibited by these T&Cs.
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
name: DoubleVerify
provenance_date: '2026-11-09'
provider_name: DoubleVerify
provider_slug: doubleverify
slug: doubleverify-eligibility
source_date: '2026-11-09'
source_filename: doubleverify-eligibility.yml
source_heading: Eligibility
source_page: https://doubleverify.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DoubleVerify\naid: doubleverify\nurl: https://doubleverify.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or prohibited use\n  text: You are strictly prohibited from using the Websites for any purpose that is considered unlawful or prohibited\n    by these T&Cs.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/doubleverify/eligibility/doubleverify-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from DoubleVerify's own page on 2026-11-09.
synthetic: false
tags:
- Ad Verification
- Ad Measurement
- Media Quality
- Brand Suitability
- Viewability
- Attention Measurement
- Invalid Traffic
- Fraud Prevention
- Contextual Targeting
- Programmatic Advertising
- Connected TV
- Social Media Measurement
- Commerce Media
- Publisher Analytics
- MRC Accredited
- AdTech
---
