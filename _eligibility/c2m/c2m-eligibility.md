---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: When you create an account with us, you guarantee that you are above the age of 18
    value: '18'
  restricted_uses:
  - summary: Sexually explicit content
    text: Pornographic or sexually explicit content.
  - summary: Impersonation
    text: Impersonating someone else
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
name: C2M
provenance_date: '2026-11-09'
provider_name: C2M
provider_slug: c2m
slug: c2m-eligibility
source_date: '2026-11-09'
source_filename: c2m-eligibility.yml
source_heading: Eligibility
source_page: https://connected2.me/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: C2M\naid: c2m\nurl: https://connected2.me/en/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Sexually explicit content\n  text: Pornographic or sexually explicit content.\n- summary: Impersonation\n  text: Impersonating someone else\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: When you create an account with us, you guarantee that you are above the age of 18\n"
source_yaml_url: https://artifacts.apis.io/c2m/eligibility/c2m-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from C2M's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Social
- Messaging
- Chat
- Mobile
- Communications
- Consumer
---
