---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Be at least 18 years old or have legal capacity to enter into contracts
    value: '18'
  restricted_uses:
  - summary: Illegal purposes
    text: Use the Service for any illegal purpose or in violation of any laws
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Aqta is not sold self-serve. Access is granted under a written pilot or licence agreement
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Aqta
provenance_date: '2026-11-09'
provider_name: Aqta
provider_slug: aqta-ai
slug: aqta-ai-eligibility
source_date: '2026-11-09'
source_filename: aqta-ai-eligibility.yml
source_heading: Eligibility
source_page: https://aqta.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aqta\naid: aqta-ai\nurl: https://aqta.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal purposes\n  text: Use the Service for any illegal purpose or in violation of any laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Aqta is not sold self-serve. Access is granted under a written pilot or licence agreement\nminimum_age:\n  value: '18'\n  text: Be at least 18 years old or have legal capacity to enter into contracts\n"
source_yaml_url: https://artifacts.apis.io/aqta-ai/eligibility/aqta-ai-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from Aqta's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Verification
- Transparency
- Dublin
- Startups
---
