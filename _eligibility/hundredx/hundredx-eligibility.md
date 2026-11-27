---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: To participate in HXC as an HXC Feedback Provider, you must reside in the United States (unless participating in an HXC program explicitly offered in another jurisdiction, in which case, you must reside in that specific jurisdiction)
  entity_types:
  - text: You may not be a Feedback Provider unless you are at least 18 years old.
    type: individual
  minimum_age:
    text: You may not be a Feedback Provider unless you are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Commercial use of Website
    text: Use the Website for any commercial purpose, or for any purpose that is fraudulent or otherwise tortious or unlawful.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We reserve the right at our discretion to request verification of, or verify on your behalf, any information provided by you, including the information provided in your Account profile.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: HundredX
provenance_date: '2026-11-09'
provider_name: HundredX
provider_slug: hundredx
slug: hundredx-eligibility
source_date: '2026-11-09'
source_filename: hundredx-eligibility.yml
source_heading: Eligibility
source_page: https://hundredx.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HundredX\naid: hundredx\nurl: https://hundredx.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: To participate in HXC as an HXC Feedback Provider, you must reside in the United States (unless participating\n    in an HXC program explicitly offered in another jurisdiction, in which case, you must reside in that specific\n    jurisdiction)\nentity_types:\n- type: individual\n  text: You may not be a Feedback Provider unless you are at least 18 years old.\nrestricted_uses:\n- summary: Commercial use of Website\n  text: Use the Website for any commercial purpose,\
  \ or for any purpose that is fraudulent or otherwise tortious\n    or unlawful.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We reserve the right at our discretion to request verification of, or verify on your behalf, any information\n    provided by you, including the information provided in your Account profile.\nminimum_age:\n  value: '18'\n  text: You may not be a Feedback Provider unless you are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/hundredx/eligibility/hundredx-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from HundredX's own page on 2026-11-09.
synthetic: false
tags:
- Customer Experience
- Consumer Insights
- Market Research
- Alternative Data
- Investment Research
- Data Licensing
---
