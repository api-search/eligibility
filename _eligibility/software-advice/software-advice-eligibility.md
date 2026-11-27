---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The terms “you” or “your” mean the business professional that accesses or uses the Site.
    type: business
  minimum_age:
    text: (a) are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: No personal or household use
    text: and not for personal, family, or household use
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
name: Software Advice
provenance_date: '2026-11-10'
provider_name: Software Advice
provider_slug: software-advice
slug: software-advice-eligibility
source_date: '2026-11-10'
source_filename: software-advice-eligibility.yml
source_heading: Eligibility
source_page: https://legal.g2.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Software Advice\naid: software-advice\nurl: https://legal.g2.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The terms “you” or “your” mean the business professional that accesses or uses the Site.\nrestricted_uses:\n- summary: No personal or household use\n  text: and not for personal, family, or household use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: (a) are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/software-advice/eligibility/software-advice-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Software Advice's own page on 2026-11-10.
synthetic: false
tags:
- B2B
- Software Recommendations
- Software Reviews
- Analytics
- Gartner
---
