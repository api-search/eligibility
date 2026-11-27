---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to use NailedIt.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to use NailedIt.
    value: '18'
  restricted_uses:
  - summary: No use during real interviews
    text: Use NailedIt during a real interview or assessment. It is preparation software.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: A mock starts after you create one with your email address and a six-digit code sent to it; there is no password and no card.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Nailedit
provenance_date: '2026-11-10'
provider_name: Nailedit
provider_slug: nailedit
slug: nailedit-eligibility
source_date: '2026-11-10'
source_filename: nailedit-eligibility.yml
source_heading: Eligibility
source_page: https://nailedit.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nailedit\naid: nailedit\nurl: https://nailedit.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use NailedIt.\nrestricted_uses:\n- summary: No use during real interviews\n  text: Use NailedIt during a real interview or assessment. It is preparation software.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: A mock starts after you create one with your email address and a six-digit code sent to it; there is no\n    password and no card.\nminimum_age:\n  value: '18'\n\
  \  text: You must be at least 18 years old to use NailedIt.\n"
source_yaml_url: https://artifacts.apis.io/nailedit/eligibility/nailedit-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Nailedit's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Interview
- Mock
- Careers
---
