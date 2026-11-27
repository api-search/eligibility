---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Service is intended for visitors located within the United States. We make no representation that the Service is appropriate or available for use outside of the United States.
  entity_types:
  - text: You must be at least 13 years of age to use the Service.
    type: individual
  minimum_age:
    text: You must be at least 13 years of age to use the Service.
    value: '13'
  restricted_uses:
  - summary: No illegal or unlawful access
    text: Access to the Service from countries or territories or by individuals where such access is illegal is prohibited.
  - summary: Not for commercial purpose
    text: use the Service or any Materials in connection with any commercial purpose
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
name: BallerTV
provenance_date: '2026-11-09'
provider_name: BallerTV
provider_slug: ballertv
slug: ballertv-eligibility
source_date: '2026-11-09'
source_filename: ballertv-eligibility.yml
source_heading: Eligibility
source_page: https://www.ballertv.com/legal-web#terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BallerTV\naid: ballertv\nurl: https://www.ballertv.com/legal-web#terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Service is intended for visitors located within the United States. We make no representation that the\n    Service is appropriate or available for use outside of the United States.\nentity_types:\n- type: individual\n  text: You must be at least 13 years of age to use the Service.\nrestricted_uses:\n- summary: No illegal or unlawful access\n  text: Access to the Service from countries or territories or by individuals where such\
  \ access is illegal is prohibited.\n- summary: Not for commercial purpose\n  text: use the Service or any Materials in connection with any commercial purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years of age to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/ballertv/eligibility/ballertv-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from BallerTV's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Entertainment
- Sports
- Video Streaming
- Live Streaming
- Media
- Youth Sports
- Recruiting
---
