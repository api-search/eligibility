---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - EU
    text: The Sites are directed to residents of North America and the European Union and the laws of California and the United States apply.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Automated access and AI training
    text: Use bots, scripts, crawlers, or other automated tools to access the Sites, Services, or Documentation
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
name: Theretailequation
provenance_date: '2026-11-10'
provider_name: Theretailequation
provider_slug: theretailequation
slug: theretailequation-eligibility
source_date: '2026-11-10'
source_filename: theretailequation-eligibility.yml
source_heading: Eligibility
source_page: https://www.theretailequation.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Theretailequation\naid: theretailequation\nurl: https://www.theretailequation.com/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - EU\n  excluded: []\n  text: The Sites are directed to residents of North America and the European Union and the laws of California and\n    the United States apply.\nentity_types: []\nrestricted_uses:\n- summary: Automated access and AI training\n  text: Use bots, scripts, crawlers, or other automated tools to access the Sites, Services, or Documentation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/theretailequation/eligibility/theretailequation-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Theretailequation's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Retail
- Returns
- Fraud Prevention
- Transaction Authorization
- Analytics
- Loss Prevention
---
