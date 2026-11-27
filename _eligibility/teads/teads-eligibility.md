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
  - summary: Unlawful or prohibited use
    text: not use the Site for any purpose that is unlawful or prohibited by these Terms
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You can simply visit and use the Site and you do not need to register with Teads to do so.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Teads
provenance_date: '2026-11-10'
provider_name: Teads
provider_slug: teads
slug: teads-eligibility
source_date: '2026-11-10'
source_filename: teads-eligibility.yml
source_heading: Eligibility
source_page: https://www.teads.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Teads\naid: teads\nurl: https://www.teads.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or prohibited use\n  text: not use the Site for any purpose that is unlawful or prohibited by these Terms\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You can simply visit and use the Site and you do not need to register with Teads to do so.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/teads/eligibility/teads-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Teads's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Advertising
- AdTech
- Video Advertising
- Conversions API
- Contextual Advertising
- Mobile SDK
- Conversational AI
---
